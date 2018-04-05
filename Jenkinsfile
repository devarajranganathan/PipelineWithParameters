pipeline{
    
    agent{
        node{
            label 'master'
        }
    }
    
    stages{
        
        stage('Stage 1'){
            steps{
                bat(script:"C:\\Devaraj\\Test\\" + "${strFileName}",returnStatus:true,returnStdout:true)
            }            
        }
    }
}