pipeline {
    agent { docker 'python' }

    stages {
        stage('build') {
            steps {
                sh 'echo "测试开始 run run run"'
                sh 'pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple'
                sh 'python test.py'
            }
        }
    