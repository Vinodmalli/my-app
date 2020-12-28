node {
    stage('SCM checkout'){
        git 'https://github.com/Vinodmalli/my-app'
    }
    stage('compile-pkg'){
        tool name: 'maven', type: 'maven'
        sh 'mvn package'
    }
}
