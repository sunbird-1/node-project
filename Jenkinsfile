pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git branch: --extra-vars '{"branch":"${params.branch}"}', url: 'https://github.com/rituparna1997/node-project.git'
            }
        }
        stage('build') {
            steps {
                sh 'cd /var/lib/jenkins/workspace/build'
                sh 'sudo docker build -t rituparna1997/myimg .'
                
            }
        }
    }
}
