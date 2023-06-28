pipeline {

    agent any 
    environment {
        ENV_URL = "pipeline global"
    }

  triggers { cron ('*/1 * * * *')

  }

    stages {

        stage( 'stage one ') {
            steps {

                echo "this is stage one "
                echo "name of the URL is ${ENV_URL}"
            }
       
       }
   stage( 'stage two ') {
            steps {
                
                echo "this is stage one "
            }
        }
    stage( 'stage three ') {
            steps {
                
                echo "this is stage one "
            }
        }
    }

}

