pipeline {
    agent any

    stages {
        stage("check out code") {

            steps {
                echo 'Checking out code.....'
            }
        }
        stage("perform lint check") {

            steps {
                    echo 'Performing Linting.....'
            }
        }

        stage("Build Code") {

            steps {
                echo 'Performing Build.....'
            }
        }

        stage("Unit Test") {

                    steps {
                        echo 'Runing Unit tests.....'
                    }
                }

        stage("Deploy") {

            steps {
                echo 'Performing Deploy.....'
            }
        }

         stage("Acceptance testing") {

            steps {
                    echo 'Performing Acceptance Tests.....'
            }
         }
    }

}