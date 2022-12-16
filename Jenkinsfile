pipeline {
    agent any

    stages {
        stage('Test case 1') {
            when {
                expression { params.testCase == "TestCase1" }
            }
            tools { 
                maven 'maven-3.8.6'
            }
            steps {
                sh 'mvn -Dtest=TestCase1 test'
            }
        }
    }
}