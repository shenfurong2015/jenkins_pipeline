#!/usr/bin/env groovy
pipeline {
  agent any

  stages {
    stage('Build') {
        steps {
            echo '#### dev branch ####'
            echo 'Building..'
        }
    }
    stage('Test') {
        steps {
            echo 'Testing..'
        }
    }
    stage('Deploy') {
        steps {
            echo 'Deploying....'
        }
    }
  }
}
