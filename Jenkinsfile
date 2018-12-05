node{
	stage('SCM Checkout'){
		git 'https://github.com/hanumanad/webapp'
	}
	stage('Compile-Package'){
	def mvnHome = tool name: 'maven-3.5.4', type: 'maven'
      sh "${mvnHome}/bin/mvn -f D:/maveen/webapp/pom.xml package"
        }
}
