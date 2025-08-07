pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               bat 'git clone https://github.com/Ankitha19c/test-repo-jenkins.git'
               git config --global user.email "Ankitha19c"
                git config --global user.name "Ankitha"


            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}