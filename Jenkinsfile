pipeline {
    agent {dockerfile true}
    stages {
        stage ('set env'){
            steps {
                bat "set JEN_B=${env.BUILD_ID}"
                bat "echo %JEN_B%"
                
            }
        }

    }
}