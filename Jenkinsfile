node {
    checkout scm
    
    stage('build') {
       sh "sudo ansible-playbook -i /etc/ansible/playbooks/inventory/hosts /etc/ansible/playbooks/playbooks/terminatevm.yml"
   
}   
}
