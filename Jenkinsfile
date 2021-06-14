pipeline {
   agent any

   stages {
      stage ('Validation') {
         steps {
           bat 'C:\Python27\python.exe scope.py'
         }
      }
     stage ('Testingz') {
         steps {
           bat 'C:\Python27\python.exe nosy.py'
         }
      }
   }
}
