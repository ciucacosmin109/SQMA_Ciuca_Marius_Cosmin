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
        stage('Test case 2') {
            when {
                expression { params.testCase == "TestCase2" }
            }
            tools { 
                maven 'maven-3.8.6'
            }
            steps {
                sh 'mvn -Dtest=TestCase2 test'
            }
        }
        stage('Test case 3') {
            when {
                expression { params.testCase == "TestCase3" }
            }
            tools { 
                maven 'maven-3.8.6'
            }
            steps {
                sh 'mvn -Dtest=TestCase3 test'
            }
        }
    }
}