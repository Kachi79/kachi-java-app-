@Library('Jenkins-Shared-Library') _

pipeline {


    agent any

    stages {

        stage('Git Checkout') {

            steps{    
            checkout{
                branch: "main"
                url: "https://github.com/Kachi79/Kachi_java_app.git"
                
                }
             }
         }
       }
    
}
