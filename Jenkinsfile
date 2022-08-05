enkinsfile (Scripted Pipeline)
/* Requires the Docker Pipeline plugin */
node('docker') {
    stage('Build') {
        docker.image('maven:3.8.4-openjdk-11-slim').inside {
            sh 'mvn --version'
        }
    }
}
