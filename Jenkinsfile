pipeline {
agent any

  stages {
    stage('Ansible Playbook Execution') {
      steps {
        sh '''
        ansible-playbook play.yml
        '''
      }
    }
    
  }
}
