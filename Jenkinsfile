#!/usr/bin/env groovy
pipeline {
    agent { docker { image 'python:3.6.9' } }
    triggers{ pollSCM('* * * * *') }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
        stage("List") {
            steps{
               sh 'ls -ltr'
               echo 'ravi'
           }
      }

    }
}
