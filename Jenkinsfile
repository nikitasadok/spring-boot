pipeline {
	agent any

	stages{
		stage('BUILD'){
			steps{
				sh 'cd /var/lib/jenkins/workspace/env.JOB_BASE_NAME/spring-boot-tests/spring-boot-smoke-tests/spring-boot-smoke-test-web-ui'
				sh 'mvn clean install'				
			}
		}
	
	}
}

