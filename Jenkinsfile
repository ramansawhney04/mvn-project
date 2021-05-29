pipeline {
    agent any
    tools {
        maven 'apache-maven-3.0.1' 
    }
    stage('checkout from git') {
     steps {
       //hello  
       git branch: 'master',
         credentialsId: 'git-creds',
         url: 'https://github.com/ramansawhney04/test.git'
       }
    }
}
