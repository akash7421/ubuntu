pipeline {
    agent any

    stages {
        stage('compile stage') {
            steps {
                with maven(maven : 'maven_3_5_0')
                    sh 'mvn clean compile'
            }

         
        }
    }
}

