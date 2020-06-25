pipeline {
   agent any
   
   stages {
      stage('Mvn package') {
         steps {
            mvn package
         }
      }
   }

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
   }
}
