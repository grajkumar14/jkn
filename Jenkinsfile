pipeline {
    agent any

    stages {
        stage('System details 1st stage') {
            steps {
                script {
                   sh 'uname -a'
                       }
                }
            }

        stage('Memory Details 2nd stage') {
            steps {
               script {
                   sh 'free -m'
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

        stage('Timing According to india +5:30UTC 7th stage') {
            steps {
               script {
                  sh 'TZ="Asia/Kolkata" date'
                      }
                }
            }
        }
    }
