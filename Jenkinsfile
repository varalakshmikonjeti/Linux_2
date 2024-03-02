pipeline {
    agent any

    
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/varalakshmikonjeti/Linux_2.git'

                // Run Maven on a Unix agent.
                sh "java Demo.java"

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }


        }
    }
}
