pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'cd /var/lib/jenkins/workspace/build'
                sh 'sudo docker build -t rituparna1997/myimg .'
                
            }
        }
    }
}
