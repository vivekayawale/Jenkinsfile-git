pipeline{
agent {
label {
    label "built-in"
	customWorkspace "/data/"
}
}

    stages{
       stage ('first'){
	            steps{
				  sh "echo 'hello all' > dev.html"
				}
		}
	   stage ('second'){
	            steps{
				  sh "echo 'second file' > dev1.html"
				}
	   }
	   
   }
}
