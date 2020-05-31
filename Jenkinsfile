pipeline {
  agent any
  stages {
     stage('Checking out source code') {
       steps {
        echo "Checking out source code"
        checkout scm
       }
     }
     stage('buiding project') {
       steps {
        echo "Building project ..."
        dir('hello-world') {
          sh 'ls -la'
        }
       }
     } 
  }
}
