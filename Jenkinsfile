pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'apt install openjdk-11-jdk'
                sh 'add-apt-repository ppa:cwchien/gradle'
                sh 'apt-get update'
                sh 'apt-get install gradle'
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