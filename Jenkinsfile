@Library('Kogito_Images') _
buildAndTestImages()
node('jenkins-slave'){
    stage('Finishing'){
        sh "docker rmi \$(docker images -q) || date"
    }
}
