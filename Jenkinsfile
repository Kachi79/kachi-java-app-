@Library('Jenkins-Shared-Library') _ 

pipeline{
  
    agent any 

    stages{

        stage('Git Checkout'){

            steps{
            checkout(
                scmGit(
                    branches: [[name: 'main']],
                    userRemoteConfigs: [[url: "https://github.com/Kachi79/kachi-java-app-.git"]]
                )
           )


            }
        }
    }




}




// @Library('Jenkins-Shared-Library') _

// pipeline {


//     agent any

//     stages {

//         stage('Git Checkout') {

//             steps{    
//             checkout{
//                 branch: "main",
//                 url: "https://github.com/Kachi79/Kachi_java_app.git"
                
//                 }
//              }
//          }
//        }
    
// }
