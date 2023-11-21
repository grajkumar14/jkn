pipeline {
    agent {
        label 'Node-1'
    }

    stages {
        stage('Print user') {
            steps {
                script {
                   sh 'whoami'
                       }
                }
            }

        stage('Print message') {
            steps {
               script {
                   sh 'echo "This is my first pipeline project"'
                      }
                }
            }

        stage('CPU Detalis 3rd stage') {
            steps {
               script {
                   sh 'lscpu'
                      }
                }
            }

        stage('Today\'s Date 4th stage') {
            steps {
               script {
                   sh 'date'
                      }
                }
            }

        stage('Uptime 5th stage') {
            steps {
               script {
                  sh 'uptime'
                      }
                }
            }

        stage('Total block devices') {
            steps {
               script {
                  sh 'lsblk'
                      }
                }
            }
        }
    }
