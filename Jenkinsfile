pipeline{
    agent any
    tools{
       maven 'Maven-3.6'
       }
    stages{
        stage('chekcout'){
            steps{
                git 'https://github.com/Dhaamodharan/my-app.git'
                }
              }
        stage('build'){
            steps{
                sh 'mvn clean package'
              }
        }
        stage('deploy'){
            steps{
                echo 'deployment of maven is success'
              }
        }
    }
}
pipeline {
         agent any
         tools {
         maven 'Maven 3.8.1'
}
         stages {
                 stage ('Checkout') {
                     steps {
                         git 'https://github.com/BasilKhan0291/MyApp.git'
                    }
         }
                 stage ('Build') {
                     steps {
                         sh 'mvn clean package'
                    }
         }
                 stage ('Notification') {
                     steps {
                         echo 'success'
                    }
         }
    }
}
