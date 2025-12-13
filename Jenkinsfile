pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh ''' test.py
               '''
            }
        }
        stage('Test') { 
            steps {
               echo "hello2"
            }
        }
        stage('Deploy') { 
            steps {
              
                sh ''' ello.py
               '''

            }
        }
    }
}


