pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    git branch: 'main', credentialsId: 'git_credential', url: 'https://github.com/kumaryadav989/sampleapp.git'

                }
            }
        }
    }
        
}