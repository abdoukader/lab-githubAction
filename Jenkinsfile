pipeline {
    agent any
    stages {
        stage(‘Build’) {
            steps {
                sh "/usr/local/Cellar/maven/3.9.5/libexec/bin/mvn clean package"
            }
        }
        stage(‘Test’) {
            steps {
                sh "/usr/local/Cellar/maven/3.9.5/libexec/bin/mvn test"
            }
        }
    }
}
