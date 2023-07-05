pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    environment {
        // Retrieve the BRANCH_NAME parameter from upstream
        def branchName = params.BRANCH_NAME ?: 'main'
    }
}
