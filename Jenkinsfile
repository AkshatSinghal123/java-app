pipeline {

    agent any

    stages {

        stage("Git Checkout"){
            steps {
                git branch: 'main', url: 'https://github.com/AkshatSinghal123/java-app'
            }
        }

        stage("Unit Testing"){
            steps {
                sh 'mvn test'
            }
        }
    }
}
