pipeline 
{   
    agent any
    stages 
    {
        stage('Verify Version') 
        {
            steps 
            {
                bat 'php --version'
            }
        }
        stage('Index') 
        {
            steps 
            {
                bat 'php index.php'
            }
        }        
    }
}
