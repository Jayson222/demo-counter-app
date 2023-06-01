pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{
                git 'https://github.com/Jayson222/demo-counter-app.git'
            }
        }
        stage('UNIT Testing'){

            steps{
                sh 'mvn test'
            }
        }
    }
}