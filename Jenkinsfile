pipeline {
    agent any
     
    //tools Jenkins needs to find installed on the machine it is hosted on
    tools {
        maven 'maven-3.5.3'
    }
  
    //stages depicts each Milestone that the build has to complete and pass to be successfully deployed.
    stages {
        stage ('Initialize') {
            steps {
 
                echo 'This is a minimal pipeline.'
            }
        }

        stage ('Dummy Maven Operation') {
            steps {
                sh 'mvn --version'
            }
        }
 
    }
}
