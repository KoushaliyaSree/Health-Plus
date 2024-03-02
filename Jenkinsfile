pipelline{
    agent any

          environment {
        NODEJS_HOME = tool 'NodeJS' // Assuming NodeJS is configured as a tool in Jenkins
             }

        stages{
            stage('Build'){
                steps {
                    sh 'echo "Building the project"'
                }
            }
            
            stage('Test'){
                steps {
                    sh 'echo " Running tests"'
                }
            }

            stage('Deploy') {
            steps {
                // Define deployment steps here
                echo "Deploying the project"
            }

            }

        }
        
        }
        //hello