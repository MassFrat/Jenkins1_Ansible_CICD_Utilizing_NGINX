pipeline {
    agent any
    
    stages {
#?      stage("SCM checkout") {
            steps {
#?              git "http://" 
            }
        }
        
        stage("Execute Ansible") {
            steps {
#?              ansiblePlaybook credentialsId: 'private-key',   
                                 disableHostKeyChecking: true,
                                 installation: 'Ansible',
                                 inventory: 'inventory',
                                 playbook: 'deployment.yml'
            }    
        }    
    }
}
