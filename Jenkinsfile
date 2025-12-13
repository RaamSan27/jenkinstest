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
               sh ''' python3 test.py
                '''
            }
        }
        stage('Deploy') { 
            steps {
              sh ''' python3 hello.py
                '''
            }
        }
    }
}


