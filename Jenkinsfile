pipeline {
    agent any
 
    stage("Execute Ansible Playbook") {
        steps {
           ansiblePlaybook 
               credentialsId: 'ansible_ssh_key',   
               disableHostKeyChecking: true,
               installation: 'Ansible',
               inventory: 'inventory',
               playbook: 'deployment.yml'
            }    
        }    
    }
}
