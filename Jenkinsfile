
pipeline {
    agent any

    stages {
        stage('deploy') {
        steps {
          
            sh 'scp -r -p -o StrictHostKeyChecking=no ./responsivehtml/* hagbes@10.10.1.136:/var/www/html'

}
   
        }
        }
    }

