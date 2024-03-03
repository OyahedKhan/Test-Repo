pipeline {
    agent any

    stages {
        stage('Show Disk Space') {
            steps {
                echo 'Hello World'
                sh 'lsblk'
                sh 'pwd'
                sh 'date'
            }
        }
        stage('Build') {
            steps {
                echo 'Hello World'
                sh 'df -HT'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Production') {
            steps {
                echo 'Hello World'
                sh 'touch cal.txt'
        }
    }
    stage('Create a History-File') {
            steps {
                echo 'Hello World'
                sh "cal 2024"
        }
    }
    
    }
}
