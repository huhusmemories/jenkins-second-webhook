pipeline {
    agent any
    stages {
        stage("build"){
	    steps{
	        sh "echo Integrating Jenkins pipeline with github webhook using jenkinsfile"
                sh "ls"
                sh "python --version"
                sh "python pipeline.py"
		}
            }
        stage("deployment"){
             steps {
                 sh "echo deployment stage has been completed"
                 sh "echo good bye"
                 }
	    }
	}
}
