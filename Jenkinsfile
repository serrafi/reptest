node {
    def docker_app
    stage('checkout git rep') { // for display purposes
        git credentialsId: 'ibraboy', url: 'https://github.com/serrafi/reptest'
        
    }
    stage('docker  image ') {
        sh 'docker images'
    }   
}
