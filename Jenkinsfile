pipeline {
    agent any

    stages {
        stage ('Build Stage') {

            steps {
                withMaven(maven : 'maven_3_6_3'){
                    
                    sh 'mvn clean compile'
                }
                
            }
        }
    }
}
