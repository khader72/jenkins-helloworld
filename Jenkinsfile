node {
    stage('clone'){
         git 'https://github.com/khader72/jenkins-helloworld.git'
            
    }
    stage('build') {
         
        sh '''javac Main.java'''
    }
    stage('run') {
        sh 'java Main'
    }
}
