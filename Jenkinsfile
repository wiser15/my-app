node{
    stage('SCM Checkout'){
        git 'https://github.com/wiser15/my-app'
    }   
    stage ('Compile-Package') {
    sh 'mvn package'
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
