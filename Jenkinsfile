pipeline{
    agent any
    stages{
        stage('hola_mundo'){
            steps{
                sh 'echo "Hola mundo_dev"'
            }
        }
        stage('cat_readme'){
            when {
                branch "dev"
            }
            steps{
                sh 'cat README.md'
            }
        }
    }    
}