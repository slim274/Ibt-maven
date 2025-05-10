pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
         stage('abbey') {
            steps {
                echo 'Hello abbey'
            }
        }

          stage('sl') {
            steps {
                echo 'Hello slim'
            }
        }

 stage('ahmed') {


     when{
         expression{

             
             $env.BRANCH_NAME == 'main'
         }
     }
       
            steps {
                echo 'Ahmed'
            }
        }


 stage('pretty') {
            steps {
                echo 'pretty'
            }
        }


    }
}
