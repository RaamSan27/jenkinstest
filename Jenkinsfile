pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "hello1"
            }
        }
        stage('Test') { 
            steps {
               sh ''' test.py
                '''
            }
        }
        stage('Deploy') { 
            steps {
              sh ''' hello.py
                '''
            }
        }
    }
}


