pipeline {
    agent {
        docker {
            image 'bravinwasike/react-js' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install'
                echo 'testing..'
            }
        }
    }
}
