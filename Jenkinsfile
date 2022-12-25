pipeline {
    agent any
    stages {
        stage ("Git checkout") {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Strvsuri/Java-techie-jt-devops-automation']]])
            }
        }
    }
}
