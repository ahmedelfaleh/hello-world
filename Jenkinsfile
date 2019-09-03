// Declarative //
pipeline {
    agent any
        stages {
            stage('Clone from github repo') {
                steps {
                    sh "ls -ll"
        }
    }
            stage('Test') {
                steps {
                    echo 'Testing hello_world.py file...'
                    sh "python -t hello_world.py"
        }
    }
            stage('Deploy') {
                steps {
                    echo 'Deploying the code ....'
                    sh "python hello_world.py"
                }
            }
        }
    }
