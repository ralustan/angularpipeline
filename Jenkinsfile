node('docker') {
    stage('Checkout') {
        scm checkout
    }
  
    stage 'Build'
    sh "./gradlew build"
}
