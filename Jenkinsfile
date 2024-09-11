pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Clone the repository
                git 'https://github.com/Asad7980/hello_world-'
            }
        }

        stage('Display Hello World') {
            steps {
                // Print the contents of hello_world.txt
                sh 'cat hello_world.txt'
            }
        }
    }
}
