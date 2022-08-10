node {
    stage('clone') {
        sh 'rm -rf *'
        git branch: 'main', url: 'https://github.com/AlainGiresEbouelNzom/hello-wolrd.git'
    }
    stage('Build') {
        sh 'touch testFile'
    }
    stage('run') {
        sh 'cat Hello.java'
    }
}
