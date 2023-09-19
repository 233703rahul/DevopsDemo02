

node {
    stage('Checkout') {
        checkout scm
    }
    stage('Build') {
        sh './build.sh'
    }
    stage('Test') {
        sh './test.sh'
    }
    stage('Deploy') {
        sh './deploy.sh'
    }
    stage('Notify') {
        sh './notify.sh'
    }
}