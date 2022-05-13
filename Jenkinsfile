#!/usr/bin/groovy
pipeline {
	agent any

	stages {

		stage('Build') {
			steps {
				echo 'Building..'
			}
		}

		stage('Test') {
			steps {
				echo 'sonarqube..'
			}
		}

		stage('Fortify') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
