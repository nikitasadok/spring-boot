pipeline {
	agent any

	stages{
		stage('BUILD'){
			steps{
				withMaven(maven : 'maven_3_5_0'){
				sh 'mvn clean install'}
			}
		}
	
	}
}

