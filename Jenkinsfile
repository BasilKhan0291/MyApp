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