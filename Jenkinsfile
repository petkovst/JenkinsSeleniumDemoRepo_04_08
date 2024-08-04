pipeline {
    agent any

    stages{
        stage("Checkout code") {
             //checkout the repository
             steps{
                get branch: 'main', url: 'https://github.com/petkovst/JenkinsSeleniumDemoRepo_04_08'
             }
        }
        stage("Set up .Net Core") {
            //install dot net
        }
         stage("restore dependencies") {
            //install dependencies
        }
        stage("Build") {
            //build
        }
        stage("Run Testa") {
            //run tests
        }
    }
}