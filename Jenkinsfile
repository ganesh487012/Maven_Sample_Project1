pipeline{
   agent any
   tools{
	maven 'MAVEN3'
   }  
   stages{
       stage('bulid package'){
           steps{
		sh 'mvn package'
 	   }
       }
       stage('Execute'){
           steps{
               sh 'java -jar target/java-project2-1.4.jar'
 	   }
       }
   }
}
