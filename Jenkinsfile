@Library('test-library') _

pipeline {
    agent any

    stages {
        stage('Git SHA') {
            steps {
                script {
		    sayHello('Samuel')

                    def sha = getGitSha()
                    echo "Git SHA: ${sha}"
                }
            }
        }
    }
}
