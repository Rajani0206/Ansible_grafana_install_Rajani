pipeline
{ 
    agent { label 'slave' }
    stages
    {
        stage("checkout scm"){
            steps{
                checkout scm          
            }            
        }
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook grafana_install.yml"
                
            }            
        }
    }
}
