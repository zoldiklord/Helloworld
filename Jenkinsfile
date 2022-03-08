node {
    stage('clone') {
    git branch: 'main', url: 'https://github.com/zoldiklord/Helloworld.git'
}
stage('build') {
   sh 'javac Main.java'
}
stage('run') {
    sh 'java Main'
}
    
}
