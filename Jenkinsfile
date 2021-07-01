node{
   stage('SCMCheckout'){
   git 'https://github.com/chanikya1054/Demo.git'
   }
   stage('Compile-package')
   {
      def mvnHome = tool name: 'Maven1', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
}
