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

            stage('deploy'){
                steps {
                    print("DEPLOY STAGE")
                }
            }

        }
    }
}