node {
    stage('SCM checkout'){
        git 'https://github.com/Vinodmalli/my-app'
    }
    stage('compile-pkg'){
        def x = tool name: 'maven', type: 'maven'
        sh "${x}/bin/mvn package"
    }
}
