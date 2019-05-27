pipeline {
    agent any
    stages {
        stage('SCM') {

            steps {

                       git "https://github.com/saurabhsonje/sonar.git"
                //

            }

        }

        stage('Test') {

            steps {

                sh "mvn package"

                //

            }

        }

        stage('Deploy1') {

            steps {

                  echo "this is step1"

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




