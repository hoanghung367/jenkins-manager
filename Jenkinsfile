pipeline {
    agent {
        docker { image 'node' }
    }
    
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
    // stages {
    //     stage('Build') {
    //         steps {
    //             sh '''
    //               docker version
    //               docker info
    //               docker compose version
    //               curl --version
    //               jq --version
    //             '''
    //         }
    //     }
    //     stage('Test') {
    //         steps {
    //             echo 'Testing..'
    //         }
    //     }
    //     stage('Test') {
    //         steps {
    //             echo 'Testing..'
    //         }
    //     }
    //     stage('Deploy') {
    //         steps {
    //             echo 'Deploying....'
    //         }
    //     }
    // }
}