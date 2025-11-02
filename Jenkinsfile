pipeline {
	agent any
    stages {
        stage('deploy on k8 ') {
            steps {           
                        sh 'pwd'
                        sh 'cp -R helm/* .'
		        sh 'ls -ltr'
                        sh 'pwd'
sh '/usr/local/bin/helm upgrade --install petapp petclinic  --set image.repository=cicdcontainer/petapp  --set image.tag=1'

				
            }           
        }
    }
}
