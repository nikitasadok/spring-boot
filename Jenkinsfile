pipeline {
	agent any

	stages{
		steps{
		stage('BUILD'){
			withMaven(maven : 'maven_3_5_0'){
				sh 'mvn clean install'
			}
		}
	

}
}
}
