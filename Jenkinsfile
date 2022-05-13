#!/usr/bin/groovy
pipeline {
	agent any

	stages {

		stage('Fortify Scan') {
			steps {
				echo 'Building..'
			}
		}

		stage('Peforming Unit Test') {
			steps {
				echo 'sonarqube..'
			}
		}

		stage('Performing Sonar Analysis') {
			steps {
				echo 'Deploying....'
			}
		}
		
		stage('Peforming IQ Scan') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
