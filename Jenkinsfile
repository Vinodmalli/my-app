node {
    stage('SCM checkout'){
        git 'https://github.com/Vinodmalli/my-app'
    }
    stage('compile-pkg'){
        sh 'mvn package'
    }
}
