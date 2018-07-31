Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'mypipeline' } }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
