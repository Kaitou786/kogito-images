@Library('Kogito_Images') _
node{
    buildAndTestImages()
    stage('Finishing'){
        sh "docker rmi \$(docker images -q) || date"
    }
}
