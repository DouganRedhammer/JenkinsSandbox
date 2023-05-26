pipeline {
    agent any
    environment {
        msbuild = '%VS160COMNTOOLS%../../MSBuild/Current/Bin/MSBuild.exe'
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
