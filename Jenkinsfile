pipeline {
    agent any
    environment {
        msbuild = '%VS160COMNTOOLS%../../MsBuild/Current/Bin/msbuild.exe'
    }
    stages {
        stage('Checkout Stage') {
            steps {
                cleanWs()
            }
        }
        stage('Build Stage') {
            steps {
                bat """
                    REM build thesolution
                """
            }
        }
    }
}
