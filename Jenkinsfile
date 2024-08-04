pipeline {
    agent any

    stages {
        stage("Checkout code") {
             //checkout the repository
             steps {
                get branch: 'main', url: 'https://github.com/petkovst/JenkinsSeleniumDemoRepo_04_08'
             }
        }
    }
}