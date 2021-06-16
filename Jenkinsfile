pipeline {
    agent { dockerfile true }
    stages {
        // agent { dockerfile true }
        stage ('build') {
            steps {
                bat "set JEN_B=${env.BUILD_ID}"
                bat 'echo %JEN_B%'
            }
        }
    }
}
