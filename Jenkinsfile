node{
    stage('download code') {
       git 'https://github.com/BruceChen2017/demo-test.git'
    }
    stage('deploy') {
       sh 'mvn package'
    }    
    stage('run sonar') {
        sh 'mvn sonar:sonar'
    }
}