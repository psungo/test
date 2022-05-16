#!/usr/bin/groovy
pipeline {
	agent any

	stages {

		stage('Fortify Scan') {
			steps {
				echo 'Building..'
			}
		}

		stage('Performing Unit Tests') {
			steps {
				echo 'sonarqube..'
			}
		}

		stage('Performing Sonar Analysis') {
			steps {
				echo 'Deploying....'
			}
		}
		
		stage('Performing IQ Scan') {
			steps {
				echo 'Deploying....'
			}
		}

		stage('Post Build Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
