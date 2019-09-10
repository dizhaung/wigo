pipeline {
  agent any
  stages {
    stage('Check') {
      agent any
      steps {
        sh 'echo "OK"'
      }
    }
    stage('Build') {
      parallel {
        stage('Build DEB') {
          steps {
            sh 'echo "OK"'
          }
        }
        stage('Build RPM') {
          steps {
            sh 'echo "OK"'
          }
        }
      }
    }
    stage('Publish') {
      parallel {
        stage('Publish Debian Jessie') {
          steps {
            sh 'echo "OK"'
          }
        }
        stage('Publish Debian Stretch') {
          steps {
            sh 'echo "OK"'
          }
        }
        stage('Publish Debian Buster') {
          steps {
            sh 'echo "OK"'
          }
        }
        stage('Publish Centos') {
          steps {
            sh 'echo "OK"'
          }
        }
      }
    }
  }
}