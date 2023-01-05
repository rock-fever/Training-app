pipeline {

    agent any

    stages {

        stage('Checkout') {

            steps {

                deleteDir()

                checkout scm

            }

        }

        stage('Test') {

            steps {

                sh 'npm install'

            }

        }

    }

}
