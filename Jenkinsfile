pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Helldddddddhgjhgfdsfjhddddo world!' 
            }
        }
        stage('STage 2') {
    steps {
         sh '''#!/bin/bash
                 cd ./do
                 docker-compose up -d --build
         '''
    }
}

    }
}
