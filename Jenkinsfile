node {
    checkout scm
    
    stage('build') {
       sh "ansible-playbook -i /etc/ansible/playbooks/inventory/hosts /etc/ansible/playbooks/terminatevm.yml"
   
}   
}
