pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'sudo apt install openjdk-11-jdk'
                sh 'sudo add-apt-repository ppa:cwchien/gradle'
                sh 'sudo apt-get update'
                sh 'sudo apt-get install gradle'
                sh 'gradle wrapper'
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