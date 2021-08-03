node {
    def docker_app
    stage('checkout git rep') { // for display purposes
        git credentialsId: 'ibraboy', url: 'https://github.com/serrafi/reptest'
        
    }
    stage('docker Build image ') {
        sh 'docker build -t ibrahimserrafi/img1:latest identidock/.'
        sh 'docker images'
    }   
}
