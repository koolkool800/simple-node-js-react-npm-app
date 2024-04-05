pipeline {
    agent any
    tools {nodejs "node"}

    stages {
        stage("Build") {
            steps {
                sh "npm install"
            }
        }

        stage('Test ne') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }

    }

    
}