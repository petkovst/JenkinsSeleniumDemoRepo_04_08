pipeline {
    agent any

    stages {
        stage("Checkout code") {
             //checkout the repository
             steps {
                git branch: 'main', url: 'https://github.com/petkovst/JenkinsSeleniumDemoRepo_04_08'
             }
        }
    }
}