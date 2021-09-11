pipeline {
    agent any

    node {
        withGradle {
            sh './gradlew build'
        }
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                withGradle {
                    sh 'gradle wrapper'
                }
            }
        }

        stage('Hello1') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Hello2') {
            steps {
                echo 'Hello World'
            }
        }        


    }
}