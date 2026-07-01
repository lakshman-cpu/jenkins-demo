pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/lakshman-cpu/jenkins-demo'
                // Run the build on a Unix agent. You must have Maven installed.
                echo "hi"

                // To run Maven on a Windows agent, use
                // bat 'mvn -Dmaven.test.failure.ignore=true clean package'
            }

       
        }
    }
}
