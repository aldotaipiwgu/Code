pipeline {
    agent any
    stages {
        stage('Execute PowerShell script') {
            steps {
                powershell 'Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process -Force'
                powershell './getad.ps1'
            }
        }
    }
}
