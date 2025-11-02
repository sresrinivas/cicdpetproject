pipeline {
	agent any
    stages {
        stage('deploy on k8 ') {
            steps {           
                        sh 'pwd'
                        sh 'cp -R helm/* .'
		        sh 'ls -ltr'
                        sh 'pwd'
sh '/usr/local/bin/helm upgrade --install petclinic-app petclinic  --set image.repository=venkataganesh48/ecomm-repo --set image.tag=10'

				
            }           
        }
    }
}
