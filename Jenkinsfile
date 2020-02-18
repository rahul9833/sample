node{
   stage('SCM checkout'){
     git 'https://github.com/rahul9833/sample'
   }
   stage('compile-package'){
      //Get maven home path
      def mvnHome = tool name: 'maven', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
   
}  
