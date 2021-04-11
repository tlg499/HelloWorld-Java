node {
    stage('Clone') {
    git branch: 'main', url: 'https://github.com/tlg499/HelloWorld-Java.git'
}
    stage('Test') {
    sh 'javac HelloWorld.java'
}
    stage('Run') {
    sh 'java HelloWorld'
}
}
