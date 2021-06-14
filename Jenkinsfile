pipeline {
   agent any

   stages {
      stage ('Validation') {
         steps {
           sh 'python scope.py'
         }
      }
     stage ('Testings') {
         steps {
           sh 'python nosy.py'
         }
      }
   }
}
