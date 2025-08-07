pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               bat '''
git init 
git add . 
 git commit -m " first commit "
git push origin master 
echo Done 
'''

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