pipeline {
    agent any


    stages {

        stage('Hello') {
            steps {
                echo 'Hello World'
                withGradle {
                    sh './gradlew -v'
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