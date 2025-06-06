// Declarative Pipeline
pipeline {

    // specifies where the pipeline or stage will run.
    agent any

    // where the work happens
    stages {

        stage("build") { 
            steps {
                echo "Building the application..."
            }
        }

        stage("test") { 
            steps {
                echo "testing the application..."
            }
        }

        stage("deploy") { 
            steps {
                echo "deploying the application..."
            }
        }

    }
}
