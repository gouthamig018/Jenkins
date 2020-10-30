pipeline{
agent any
stages{
stage("checkout"){
steps{
checkout([$class: 'GitSCM',
branches: [[name: '*/master']],
userRemoteConfigs: [[credentialsId: '0e198f06-088d-47a1-8091-bbbc77b205ed', url: 'https://github.com/gouthamig018/Jenkins.git']]])
}
}
}
}
