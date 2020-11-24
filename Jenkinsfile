pipeline {
    agent any
        stages {        
        stage('Pre Build') {
            steps {

			    script {
                    sh 'echo "job1"'
			    }
            }
        }
		stage("trigger full build") {
        build job: 'job2', wait: false
    }
    }
}
