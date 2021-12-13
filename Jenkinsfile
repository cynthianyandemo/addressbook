pipeline{
    agent any
    stages{
        stage ('compilation') {
            steps {
                sh 'echo hello there. this is compilation'
            }
        }
        stage ('deployment') {
            steps {
            sh 'echo hello there.this is deployment'
            }
        }
 stage ('finalized') {
            steps {
            sh 'echo hello there.this is finalization'
            }
        }
   }
}
