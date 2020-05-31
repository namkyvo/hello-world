pipeline {
  agent any
  stages {
     stage('Checking out source code') {
        echo "Checking out source code"
        checkout scm
     }
     stage('buiding project') {
        echo "Building project ..."
       dir('hello-world') {
         sh 'ls -la'
       }
     } 
  }
}
