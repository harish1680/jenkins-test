pipeline {
    agent any
    stages {
        stage('Pull Code') {
            steps {
                git  'https://github.com/harish1680/jenkins-test.git'
            }
        }
        stage('Run Script') {
            steps {
                sh 'bash hello.sh'
            }
        }
    }
}

