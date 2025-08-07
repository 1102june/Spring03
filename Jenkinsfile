pipeline {
    agent any
    
    tools {
        maven 'my-maven'  // Jenkins Testing
    }

    stages {
        stage('0. 연결 확인') { steps { echo '스테이지 출발' } }
        
        stage('1. Build') {
            steps {
                echo 'Maven으로 빌드 시작'
                sh 'mvn clean package'
            }
        }        
    }
}
