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
                        echo "Me in stage two"
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
            
