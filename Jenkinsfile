node{
	stage('SCM Checkout'){
		git 'https://github.com/xlinkersoul/jenkins-maven-java-ee'
	}
	stage('Compile-Package'){
		def mvnHome = tool name: 'maven-360' , type: 'maven'
		sh 'echo ${mvnHome};${mvnHome}/bin/mvn package'
	}
}
