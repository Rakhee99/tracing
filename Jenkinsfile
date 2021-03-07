pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
               python reverse_list.py
            }
        }
      stage('Testing Stage'){
        steps{
          echo 'Test is completed'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
