/* Principal pipeline for the DMHS product components. */
pipeline {

	agent any   
    
    stages {
        stage('Build') {
            steps {
            	git 'https://github.com/terminalerror/jgsu-spring-petclinic.git'
            }
            post {
                echo "Successfully built"
            }
        }
       
    }
    
    post {

        always {       

        }
        
        failure {        	

        }
    }

}
