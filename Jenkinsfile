pipeline {
	agent any

	stages{
		stage('BUILD'){
			steps{
				withMaven(maven : 'maven_3_0_5'){
				sh 'mvn clean install'}
			}
		}
	
	}
}

