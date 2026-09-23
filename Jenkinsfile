pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
            checkout scm
        }}
    stage('build'){
        steps{
        bat "python py.py"
    }}}
}