@Library('test-library') _

pipeline {
    agent any

    stages {
        stage('Git SHA') {
            steps {
                script {
                    def sha = getGitSha()
                    echo "Git SHA: ${sha}"
                }
            }
        }
    }
}
