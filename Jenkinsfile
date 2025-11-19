pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/Jayashree055/mavenweb'
                bat 'mvn clean package'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying to Tomcat..."
            }
        }
    }
}
