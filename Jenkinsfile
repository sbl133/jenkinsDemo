pipeline {
   agent {
        label "demoAgent"
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                build 'SeleniumMaven'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post {
        always {
            echo 'pipline job done!!!'
        }
    }
}
