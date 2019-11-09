pipeline {
	agent any

	stages{
		stage('BUILD'){
			steps{
				def mvnHome = tool name: 'maven-3', type: 'maven'
				sh "${mvnHome}/bin/mvn clean install -f /var/lib/jenkins/workspace/CI-pipeline/spring-boot-tests/spring-boot-smoke-tests/spring-boot-smoke-test-web-ui"				
			}
		}
	
	}
}

