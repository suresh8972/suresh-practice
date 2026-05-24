pipeline {
    agent any
    tools {
        maven "mymaven"
    } 
    stages {
        stage ("code") {
            steps {
                git 'https://github.com/devops0014/one.git'
            }
        }
        stage ('BUILD') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}