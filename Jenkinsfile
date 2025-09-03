pipeline {
    agent any

    stages {
        stage('Checkmarx Scan') {
            steps {
                checkmarxASTScanner additionalOptions: '',
                        baseAuthUrl: '',
                        branchName: 'feature/jenkins',
                        checkmarxInstallation: 'latest',
                        credentialsId: '',
                        projectName: 'cx-devsecops/nodegoat',
                        serverUrl: '',
                        tenantName: '',
                        useOwnAdditionalOptions: true,
                        useOwnServerCredentials: true
            }
        }
    }
}
