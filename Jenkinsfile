pipeline {
    agent any 
       triggers {
        pollSCM "* * * * *"
       }
    stages {
        stage('Git SCM') {
            steps {
                git 'https://github.com/sureshguvva/file.git'
            }
        }
        }
}