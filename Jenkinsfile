pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_NUMBER} on ${env.JENKINS_URL}"
                echo "BRANCH_NAME is ${env.BRANCH_NAME}"
            }
        }
    }
}
