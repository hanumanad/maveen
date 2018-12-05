node{
	stage('SCM Checkout'){
		git 'https://github.com/hanumanad/maveen'
	}
	stage('Compile-Package'){
	def mvnHome = tool name: 'maven-3.5.4', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
        }
}
