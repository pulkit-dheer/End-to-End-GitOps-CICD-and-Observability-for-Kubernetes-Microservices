@Library('Jenkins-shared-library') _

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {

                    gitCheckout([
                        branch: 'main', 
                        url: 'https://github.com/pulkit-dheer/End-to-End-GitOps-CICD-and-Observability-for-Kubernetes-Microservices.git' 
                    ])
                }
            }
        }

    }
}
