pipeline {
    agent any

    stages {
        stage('Test case 1') {
            when {
                expression { params.testCase == "TestCase1" }
            }
            steps {
                sh './mvn -Dtest=TestCase1 test'
            }
        }
    }
}