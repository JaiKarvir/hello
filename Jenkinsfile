@Library('shared-library') _
pipeline {
    agent any
    tools {nodejs "node"}
    stages {
        stage('build') {
            steps {
                sh 'npm install'
                sh 'npm --version'
                script{
                    //echo "Hello"
                    qtestbaseddod();
                //def res = errorAndExceptionHandling("xyz","start_time","end_time","./DodConfig.yaml");
                //println("FinalResult: ${res}")
                }
            }
        }
    }
}