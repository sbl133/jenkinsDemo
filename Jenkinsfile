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
    }
    post {
        always {
           today=`date`
            echo $today
        }
    }
}
