pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', credentialsId: 'GitHub_Credentials', url: 'https://github.com/PradeeppaPalanisamy/sample_assign2.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
