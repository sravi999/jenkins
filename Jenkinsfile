#!/usr/bin/env groovy
pipeline {
    agent { docker { image 'python:3.6.9' } }
    triggers{ pollSCM('H/15 * * * *') }
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
