pipeline {
   agent any

   stages {
      stage ('Validation') {
         steps {
          bat '''@echo off
                     for /f "delims=" %%a in (scope.py) DO ( 
                       ECHO Line is: %%a
                     )'''
         }
      }
     stage ('Testingz') {
         steps {
          bat '"C:\\Python27\\python.exe" nosy.py'
         }
      }
   }
}
