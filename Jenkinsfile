pipeline{
    agent none
    stages{
        stage('Compile'){
            agent any
            steps{
                sh 'echo compilng'
            }
        }
        stage('Quality'){
            agent any
            steps{
                sh 'echo code quality'
            }
        }
        stage('create docker iamge '){
            agent any
            steps{
                sh 'echo docker built -t $Project:$BUILD_ID'
            }
        }
    }
}
