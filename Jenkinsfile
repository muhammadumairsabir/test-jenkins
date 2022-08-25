pipeline {
      parameters{
        choice(name: 'NAMESPACE', description: 'k8s cluster you want to deploy to', choices: ['move-dev', 'move-int', 'move-prod' ])
    }
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                script {
                    try {
                            sh 'echo sdfjskfdsfklsfjsd'
                    } catch (Exception e) {
                        error "Maybe sonar-project.properties is missing?"
                    }
                }
            }
        }
    }
}
