pipeline
{ 
    agent { label 'slave' }
    stages
    {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook grafana_install.yml"
                
            }
            
        }
    }
}
