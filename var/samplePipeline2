def call(Map pipelineParams) {

    pipeline {
        agent any
        stages {
            stage('checkout git') {
                steps {
                    print("GIT STAGE")
                }
            }

            stage('build') {
                steps {
                    print("BUILD STAGE")
                }
            }

            stage ('test') {
                steps {
                   print("TEST STAGE")
                }
            }

            stage('deploy development'){
            steps {
                print("DEPLOY STAGE - DEVELOPMENT")
            }
        }

        stage('deploy staging'){
            steps {
                print("DEPLOY STAGE - STAGING")
            }
        }
            stage('deploy production'){
                steps {
                    print("DEPLOY STAGE - PRODUCTION")
                }
            }

        }
    }
}