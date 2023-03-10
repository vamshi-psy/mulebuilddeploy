pipeline {
    agent any
    stages {   
      stage("Maven Build") {
        steps {
          echo "************* Building application version ${VERSION} ************* >"
          sh "/usr/bin/mvn clean deploy -DmuleDeploy"
          echo '<************* Build and deploy completed *************>'
        }
      }
    }
}

