pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out from GIT...1'
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'Github', url: 'https://github.com/SatyajitJC/jenkindemo.git']])
            }
        }
        stage('Build') {
            steps {
                echo 'Build......1'
            }
        }
        stage('Upload...') {
            steps {
                echo 'Upload...1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy....1'
            }
        }
	}
}
