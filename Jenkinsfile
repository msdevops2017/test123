pipeline {
    agent { label 'npe-deploy-pod' }
    stages {
        stage('build') {
            steps {
            echo $GIT_COMMIT
            }
        }
    }
}
