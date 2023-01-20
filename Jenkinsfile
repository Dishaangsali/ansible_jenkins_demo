pipeline{
    agent any
    stages {
        stage('Checkout from SCM') {
            steps {
            git 'https://github.com/Dishaangsali/ansible_jenkins_demo.git'
            }
        }
        stage('Build') {
            steps {
            sh 'ansible-playbook playbook1.yaml'
            }
        }
    }
}
