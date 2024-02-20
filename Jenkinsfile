pipeline {


   agent any

   stages {

       stage('Git Checkout') {

         steps{

             script{

                 gitCheckout{
                    branch: "main",
                    url: "https://github.com/Kachi79/kachi-java-app-.git"
                 }
             }
         }
       }
    
    }

    }     

//          pipeline {
//     agent any

//     stages {
//         stage('Git Checkout') {
//             steps {
//                 script {
//                     git branch: 'main', url: 'https://github.com/Kachi79/kachi-java-app-.git'
//                 }
//             }
//         }
//         // Add more stages as needed
//     }
// }