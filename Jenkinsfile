node {
    stage('ハローワールド') {
        sh 'echo "Hello World!!!!!!!"'
    }
    stage('gitをクローン') {
        git('https://github.com/shaream/hello_scm.git')
    }
    stage('ファイル確認') {
        sh 'ls -l'
    }
}