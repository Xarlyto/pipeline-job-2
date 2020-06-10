pipeline {
    agent any

    stages 
    {
        stage('Start') {
            steps {
                echo "Multibranch Pipeline Job 2 Starts"
            }
        }

        stage ('Do_Something') {
            steps {
                bat "Java -version"
            }
        }

        stage('End') {
            steps {
                echo "Multibranch Pipeline Job 2 Ends"
            }
        }
    }
}
