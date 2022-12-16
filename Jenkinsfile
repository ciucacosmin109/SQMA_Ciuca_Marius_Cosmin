pipeline {
    agent any

    stages {
        stage('Test case 1') {
            when {
                expression { params.testCase == "TestCase1" }
            }
            sh 'mvn -Dtest=TestCase1 test'
        }
    }
}