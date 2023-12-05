Pipeline{
    agent any
    stages{
        stage("Workspace-Cleanup"){
            steps{
                cleanWs()
            }
        }
        stage("Code-Checkout"){
            steps{
                git branch: 'main', credentialsId: 'github', url: 'https://github.com/codeisgoo/Complete-Production-Pipeline.git'
            }
        }
    }
}