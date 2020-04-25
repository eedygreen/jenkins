pipeline {
    agent any
    stages {
        stage('Upload To AWS') {
            steps {
                withAWS(region:'us-east-1', credentials:"aws-static"){
                    s3Upload(file:'index.html', bucket:'jenkinsstaticbucket')
                }
            }
        }
    }

  }
