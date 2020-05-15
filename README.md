pipeline {
   agent any

   stages {
      stage('compile') {
         steps {
            echo 'Hello Tauqueer hussain1'
         }
      }
      stage('build') {
         steps {
            echo 'Hello Tauqueer hussain2'
         }
      }
      stage('deploy') {
         steps {
            echo 'Hello Tauqueer hussain3'
         }
      }
   }
}
