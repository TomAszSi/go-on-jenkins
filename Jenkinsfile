pipeline {
     agent any
     environment {
         GO111MODULES = 'on'
     }
     tools {
         go 'go-1.13'
     }
     stages {
         stage {
             steps {
                 sh 'go build'
             }
         }
     }
}
