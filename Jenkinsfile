pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                sh 'rm -rf hello-world-war'
                sh 'git clone https://github.com/Tejasks16/hello-world-war'
            }
        }
        stage('build') {
            steps {
                dir ('hello-world-war') {
                sh 'mvn package'
                sh 'mvn package'
            }
        }
    }
}
}
