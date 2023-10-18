pipeline {
    agent any 
    options { timestamps () }

    stages {
        stage('Renew Auto Scaling') {
            steps {
                renewAutoScalingGroup("jenkins-test", "us-east-1")          
                    stages2 {
        stage('Renew Auto Scaling') {
            steps {
                renewAutoScalingGroup("jenkins-test", "us-east-1")          
            }
        }
    }
}
