pipeline {
    agent any
    stages {
        stage('test stage 1') {
            steps {
            bat 'echo "this is a sample text" > sample.txt
            archiveArtifacts allowEmptyArchive: true, artifacts: 'sample.txt', fingerprint: true, followSymlinks: false, onlyIfSuccessful: true
        }
    }
}
}
