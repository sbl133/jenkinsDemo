import java.text.SimpleDateFormat

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
           def dateFormat = new SimpleDateFormat("yyMMddHHmm")
           def date = new Date()
           def TODAY = dateFormat.format(date)
           sh "echo ${TODay}"           
        }
    }
}
