pipeline {
    agent any
    stage {
       stage('Build') {
           steps {
               sh "mvn clean"       
           
           }
        }
        stage('Test') {
            steps {
                sh "mvn test"
            
            }
         }
         stage('Deploy') {
             steps {
                 sh "mvn package"
             }
          }
      }
 }
