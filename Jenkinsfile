pipeline {
    agent any
    
    tools {
        maven 'my-maven'  // Jenkins Testing5
    }

    stages {
        stage('0. 연결 확인1606') { steps { echo '스테이지 출발' } }
        
        stage('1. Build') {
            steps {
                echo 'Maven으로 빌드 시작'
                sh 'mvn clean package'
            }
           }
            stage('2.Docker Version 확인') {
            steps {
                sh 'docker version'
            }
        }    
        
       
    }
}
