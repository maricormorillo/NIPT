pipeline 
{   
    agent any
    stages 
    {
        stage('Verify Version') 
        {
            steps 
            {
                sh 'php --version'
            }
        }
        stage('Index') 
        {
            steps 
            {
                sh 'php index.php'
            }
        }        
    }
}
