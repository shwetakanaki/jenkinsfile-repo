pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'python3 test.py' 
            }
        }
        stage('Test') { 
            steps {
            echo "stage-2"
            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}

# how to run the python file form the jenkins file
#  sh 'python3 your_script.py' 

