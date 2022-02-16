node{
    stage('SCM Checkout'){
        
        git 'https://github.com/wiser15/my-app'
    }   
    stage ('Compile-Package') {
        // Get maven Home path
        def mvnHome = tool name: 'MAVEN3.6.1', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}
        




// pipeline{
//    agent any
//   triggers {
//    pollSCM '* * * * *'
//  }
// stages{
//    stage("SCM"){
//        steps{
//          echo "job ran.....again and again"
//      }
//        }
//    }
// }
