pipeline {
    agent any
    stages {
        stage("maven build") {
            steps {
                sh "/usr/bin/mvn clean deploy -DmuleDeploy"
            }
        }
    }
}
