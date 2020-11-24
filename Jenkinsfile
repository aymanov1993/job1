pipeline {
    agent any
        stages {        
        stage('Pre Build') {
            steps {

			    script {
                    sh 'echo "job1"'
			    }
		    build job: 'job2', wait: false
		    sleep 60s
            }
        }
    }
}
