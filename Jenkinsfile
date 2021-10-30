pipeline {
    stages {
        stage('Checkout Main') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'git', url: 'https://github.com/eliabtege/awsdoc.git']]])
            }
        }
    }
}
