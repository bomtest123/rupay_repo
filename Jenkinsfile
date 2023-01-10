pipeline {
    agent any 
    stages {
        stage('STEP1') {
            steps {
                echo 'Run the static analysis to the code' 
                sh "pm2 1"
            }
        }
        stage('STEP2') {
            steps {
                echo 'Compile the source code' 
            }
        }
        stage('STEP3') {
            steps {
                echo 'Run the security check against the application' 
            }
        }
        stage('STEP4') {
            steps {
                echo 'Run unit tests from the source code' 
            }
        }
        stage('STEP5') {
            steps {
                echo 'Run only crucial integration tests from the source code' 
            }
        }
        stage('STEP6') {
            steps {
                echo 'Save the assemblies generated from the compilation' 
            }
        }
    }
}