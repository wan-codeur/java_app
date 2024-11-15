node {
    stage('clone') {
        git branch: 'main', url: 'https://github.com/wan-codeur/java_app.git'
    
    }
    stage('build') {
        sh 'javac Main.java'
    
    }
    stage('run') {
        sh 'java Main'
    
    }
}
