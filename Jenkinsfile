node{
    tools { 
    maven 'MAVEN3_HOME' 
    jdk 'JAVA_HOME' 
    stage('SCM checkout'){
        git 'https://github.com/vsknalli/secound-app'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
