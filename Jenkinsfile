pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo "build success"
            }
        }
        post{
            success{
                emailext body: 'Build successful', subject: 'Test Email', to: 'tejanani915@gmail.com'
            }
        }
    }
}
