pipeline{

    agent any

    stages{
        stage('Build'){
            steps{
                echo 'Building'
                sh 'python3 heloo.py'
            }
        }
    }

    post{
        success{
            mail to: voj.oup@gmail.com, subject: 'The Pipeline succeeded'
        }
    }
}
