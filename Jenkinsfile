pipeline {
    agent any
    stages {
         stage('one') {
                    steps {
                        echo "Me in stage one"
                    }
                }
                stage('Two') {
                    steps {
                        input ('Do you want to proceed?')
                    }
                }
                stage('Three') {
                    when{
                        not{
                            branch 'main'
                        }
                    }
                    steps {
                        echo "Me in stage Three"
                    }
                }
        stage('Four'){
            steps{
                echo 'Running unit test'
            }
            }
            stage('Five'){
                steps{
                    echo 'Running Integration Test'
                }
            }
        }
    }
    


            
        
                
               
        
            
