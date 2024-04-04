pipeline{
    agent{
        node{
            label 'Docker_JAVA'
        }
    }

    stages{
        stage('test'){
            steps{
                echo "Testign"
            }
           
        }

        stage('build'){
            steps{
                echo "build"
            }
        }

        stage('end'){
            steps{
                echo "end"
            }
        }
    }

    triggers{
        pollSCM '* * * * *'
    }
}