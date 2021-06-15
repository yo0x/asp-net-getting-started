pipeline {
    agent {dockerfile true}
    stages {
        stage ('git repo'){
            steps {
                bat "set JEN_B=${env.BUILD_ID}"
                bat "echo %JEN_B%"
            }
        }

    }
}