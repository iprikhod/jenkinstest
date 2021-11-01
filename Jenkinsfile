properties([disableConcurrentBuilds()])

pipeline {
    agent { 
        //label 'esb_worker'
        any
        }
    options {
        //buildDiscarder(logRotator(numToKeepStr: '10', artifactNumToKeepStr: '10'))
        //timestamps()
    }
    stages {
        stage("Install something 1") {
            steps {
                sh 'echo \'start ESB build\''
                //sh 'ssh esb_worker@mprdvm-esbjw01.pmru.local \'hostname\''
            }
        }
        stage("Install something 2") {
            steps {
                sh 'echo \'start ESB build\''
                //sh 'ssh esb_worker@mprdvm-esbjw01.pmru.local \'uptime\''
            }
        }
    }
}
