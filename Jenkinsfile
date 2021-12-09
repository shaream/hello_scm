node {
    stage('ハローワールド') {
        sh 'echo "Hello World!!!!???!!!?????"'
    }
    stage('gitをクローン') {
        git('https://jenkins.endcyclone.com/jenkins/github-webhook/')
    }
    stage('ファイル確認') {
        sh 'ls -l'
    }
}