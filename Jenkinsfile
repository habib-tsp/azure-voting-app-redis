pipeline {
    agent any

    stages {
        stage('Verify') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Docker Build') {
            steps {
                pwsh(script: 'Write-Output "hello wolrddd"')
            }
        }
    }
}
