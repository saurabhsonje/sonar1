pipeline {
    agent any
    stages {
        stage('SCM') {

            steps {

                       git "https://github.com/saurabhsonje/alldata.git"
                //

            }

        }

        stage('Test') {

            steps {

                sh "mvn test"

                //

            }

        }

        stage('Deploy1') {

            steps {

                  sh "/sonar-scanner/sonar-scanner/bin/sonar-runner"

            }

        }

                  stage('Deploy2') {

            steps {

                  echo "this is step2"
            }

        }
                      stage('Deploy3') {

            steps {
                       echo "this is step1"

             
            }

        }

    }

}




