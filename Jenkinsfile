pipeline {
    agent any


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