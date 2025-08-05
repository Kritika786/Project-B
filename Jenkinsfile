@Library('jenkins-shared-library') _

pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                test()
            }
        }
        stage('Notify') {
            steps {
                notify()
            }
        }
    }
}
