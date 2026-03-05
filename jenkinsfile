pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Running BUILD stage"
                sh '''
                    echo "Compiling source code..."
                    sleep 2
                    echo "Build completed!"
                '''
            }
        }

        stage('Test') {
            steps {
                echo "Running Test stage"
                sh '''
                    echo "Executing test cases..."
                    sleep 2
                    echo "All tests passed!"
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo "Running DEPLOY stage"
                sh '''
                    echo " excecuting deploy stages"
                    sleep 2
                    echo "Deployment successful!"
                '''
            }
        }

    }
}
