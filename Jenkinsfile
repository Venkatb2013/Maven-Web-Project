#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){

          bat 'mvn clean install'
	       
	       //sh 'mvn clean'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                   // sh 'mvn sonar:sonar'
	       bat 'mvn sonar:sonar'
                }
       
}
