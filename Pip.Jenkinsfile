pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello world'
                echo "VERSION: $VERSION"
            }
        }
        stage('Prepare to build..') {
            steps {
                echo 'building'
                echo "VERSION: $VERSION"
            }
        }
        stage('again building application') {
            steps {
                echo 'app building'
                echo "VERSION: $VERSION"
            }
        }
        stage('testing') {
            steps {
                echo 'testing the build'
                echo "VERSION: $VERSION"
            }
        }
        stage('deploying') {
            steps {
                echo 'deploying the project'
                echo "VERSION: $VERSION"
            }
        }
    }
}
