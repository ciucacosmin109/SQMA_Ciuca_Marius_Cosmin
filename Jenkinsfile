pipeline {
    agent any

    stages {
        stage('Test case 1') {
            when {
                expression { params.testCase == "TestCase1" }
            }
            tools { 
                maven 'MAVEN_HOME' 
                jdk 'JAVA_HOME' 
            }
            steps {
                sh 'mvn -Dtest=TestCase1 test'
            }
        }
    }
}