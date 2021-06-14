pipeline {
   agent any

   stages {
      stage ('Validation') {
         steps {
           bat 'python scope.py'
         }
      }
     stage ('Testingz') {
         steps {
           bat 'python nosy.py'
         }
      }
   }
}
