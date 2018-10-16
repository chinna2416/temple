node{
    stage('SCM Checkout'){
        git 'https://github.com/chinna2416/tasks.git'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
