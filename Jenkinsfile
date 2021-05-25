pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh 'mvn -DskipTest clean package'
            }
        }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    }
}
