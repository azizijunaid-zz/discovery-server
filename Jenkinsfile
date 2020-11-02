
pipeline {
    agent {label: 'agent007'}

    stages {
        /**stage('checkout') {
            steps {
                git url: 'https://github.com/azizijunaid/discovery-server.git' , branch: 'master'
            }
        }*/
         stage('build') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}
