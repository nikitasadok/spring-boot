pipeline {
	environment{
		mvnHome = tool name: 'maven_3_6_2', type: 'maven'
	}
	agent any

	stages{
		stage('BUILD'){
			steps{
				sh "${mvnHome}/bin/mvn clean install -f /var/lib/jenkins/workspace/CI-pipeline/spring-boot-tests/spring-boot-smoke-tests/spring-boot-smoke-test-web-ui"				
			}
		}
	
	}
}

