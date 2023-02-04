pipeline {
    agent any


    stages {
        stage('notify') {
            steps {
               emailext(body: '1111', subject: 'test', to: 'mafeifan@qq.com')
            }
        }
    }
}
