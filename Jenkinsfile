pipeline {
   agent any
   stages {
        stage('Init') {
            steps {
                script {
                    sh '''
                        echo "This is to test copying file to server" > sshtest.txt
                        ls -l
                        
                    '''
                }
            }
        }
   }
}
