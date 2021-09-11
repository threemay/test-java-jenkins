pipeline {
    agent any


    stages {

        stage('build') {
            steps {
                echo 'Hello World'
                withGradle {
                    sh './gradlew build'
                }
            }
        }

        stage('test') {
            steps {
                echo 'Hello World'
                withGradle {
                    sh './gradlew run'
                }
            }
        }

        stage('Hello2') {
            steps {
                echo 'Hello World'
            }
        }        


    }
}