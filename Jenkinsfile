pipeline {
    agent any
    
    stages {
        stage('greetings') {
            steps{
                echo 'Holla Mundos!'
            }
        }
        stage('Preparation') {
            steps{
                echo 'stage Preparation'
            }
        }
        stage('Build') {
            steps{
                echo 'stage Build'
		sh './gradlew clean test jar'
            }
        }
        stage('Results') {
            steps{
                echo 'stage Results'
            }
        }
    }
}
