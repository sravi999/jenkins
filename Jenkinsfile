#!/usr/bin/env groovy
pipeline {
    agent { 
        docker { 
            image 'python:3.6.9'
            label 'jen-controller'
            registryUrl 'https://index.docker.io/v1/'
            registryCredentialsId 'DockerHubCrds'
        } }
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
