pipeline {
    agent any
    stages {
        stage("cleanup"){
            steps {
                deleteDir()
            }
        }
        stage ("stage 1"){
          steps{
              dir("simple-app-stage"){
                echo "This is stage 1"
            }
          }
        }
        stage ("stage 2"){
          steps{
              dir("simple-app-stage"){
                echo "This is stage 2"
            }
          }
        }
        stage ("stage 3"){
          steps{
              dir("simple-app-stage"){
                echo "This is stage 3"
            }
          }
        }
        stage ("stage 4"){
          steps{
              dir("simple-app-stage"){
                echo "This is stage 4"
            }
          }
        }
        stage ("stage 5"){
          steps{
              dir("simple-app-stage"){
                echo "This is the final stage"
            }
          }
        }     

    }
}