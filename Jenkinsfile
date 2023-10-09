// Declarative way for pipeline
pipeline {
    agent any
    stages {
        stage ("init") {
            steps {
               sh "terraform init" //plan //apply //destroy
            }
        }
        stage("planning") {
            steps {
                sh "terraform plan"

            }
        }
    }

}