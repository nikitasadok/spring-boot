pipeline {
	agent any

	stages{
		stage('BUILD'){
			steps{
				withMaven(maven : 'maven_3_0_5'){
				sh './mvnw clean install'}
			}
		}
	
	}
}

