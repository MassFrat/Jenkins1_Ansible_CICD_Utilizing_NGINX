pipeline {
    agent any
 
        stage("Execute Ansible Playbook") {
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
