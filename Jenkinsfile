pipeline {
    agent any
    
    stages {
        stage('code-pull') {
            steps {
                git branch: 'main', url: 'https://github.com/iam-yuvi/two-tier-ci-cd-project.git'
            }
        }

        stage('deploy') {
            steps {
                sh 'docker-compose down || true'
                sh 'docker-compose up -d --build'
            }
        }
    }
}
