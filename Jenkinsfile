pipeline {
	agent any

	stages{
		stage('BUILD'){
			steps{
				withMaven(maven : 'maven_3_0_5'){
				sh 'mvn clean install -f /home/vagrant/spring-boot/spring-boot-tests/spring-boot-smoke-tests/spring-boot-smoke-test-web-ui pom.xml'}
			}
		}
	
	}
}

