pipeline{
    agent any
    stages{
        stage ('compilation') {
            steps {
                sh 'echo hello there. this is compilation'
                sh 'echo hello world'
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
stage ('send mail') {
            steps {
            mail bcc: '', body: 'build is finished', cc: '', from: '', replyTo: '', subject: '', to: 'cynthiafre1989@yahoo.com'
            }
        }   
}
}
