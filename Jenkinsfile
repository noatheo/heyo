pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                echo 'Helldddddddhgjhgjhdddbjkddhesfsfsfsllodddddddddddddo world!' 
            }
        }
        stage('Setting the variables values') {
    steps {
         sh '''#!/bin/bash
                 docker build -t hayo ./do
                 docker run hayo
         '''
    }
}

    }
}
