pipeline {
   agent any
   tools {nodejs "nodejs-for-react"}
   stages {
      stage('Build') {
         steps {
            sh 'npm install'
            sh 'npm run buid'
         }
      }
   }
}