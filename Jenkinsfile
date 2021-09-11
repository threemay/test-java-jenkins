node {
    stage('Hello1') {
            steps {
                echo 'Hello World'
            }
        }

    withGradle {
        sh './gradlew build'
    }
}