node{
	stage('SCM Checkout'){
		git 'https://github.com/xlinkersoul/jenkins-maven-java-ee'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}
