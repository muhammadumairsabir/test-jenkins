pipeline {
      parameters{
        choice(name: 'NAMESPACE', description: 'k8s cluster you want to deploy to', choices: ['move-dev', 'move-int', 'move-prod' ])
    }
    agent any
    stages {
        stage('Install Dependencies') {
             environment {
                scannerHome = tool 'SonarQubeScanner-4.6.2'
            }
            steps {
                script {
                    try {
                            sh 'echo sdfjsk;fdsfklsfjsd'
                    } catch (Exception e) {
                        error "Maybe sonar-project.properties is missing?"
                    }
                }
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
