#!/usr/bin/env groovy
pipeline {
    agent { docker { image 'python:3.6.9' } }
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
        stage("List") {
            steps{
               sh 'ls -ltr'
           }
      }

    }
}
