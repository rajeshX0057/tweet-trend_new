pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch:'master', url:'https://github.com/rajeshX0057/tweet-trend_new-v1.git'
            }
        }
    }
}