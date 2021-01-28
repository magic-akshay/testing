node {
   stage('clone') { 
      
      git 'https://github.com/shubham8317/testing.git'
   }
      stage('Build') { 
bat '''cd testing-master
 mvn clean'''
   
   bat '''cd testing-master
 mvn install'''
   }
}
      
      
