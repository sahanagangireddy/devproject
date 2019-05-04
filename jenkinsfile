pipeline {
    agent any
    stages {
        stage('validate stage') {
            steps {
                echo "Validate"
                git 'https://github.com/sahanagangireddy/devproject.git'
                sh '/usr/bin/mvn validate'
          }
        }
        stage('Test') {
            steps {
                echo "Test"
                git 'https://github.com/sahanagangireddy/devproject.git'
                sh '/usr/bin/mvn test' 
           }
        }
        stage('Deploy') {
            steps {
                echo "Deploy"
                
          }
        }
    }
 }
