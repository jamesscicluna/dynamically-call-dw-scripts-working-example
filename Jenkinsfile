pipeline {
    agent any
     
    //tools Jenkins needs to find installed on the machine it is hosted on
    tools {
        maven 'Maven 3.5.0'
    }
  
    //stages depicts each Milestone that the build has to complete and pass to be successfully deployed.
    stages {
        stage ('Initialize') {
            steps {
 
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                '''
            }
        }

        stage ('Dummy Maven Operation') {
            steps {
                sh 'mvn --version'
            }
        }
 
    }
}
