pipeline {
    agent any
    
    stages {
#Clone repo?stage("SCM checkout") {
            steps {
#?              git "https://github.com/MassFrat/Jenkins1_Ansible_CICD.git"
            }
        }
        
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
