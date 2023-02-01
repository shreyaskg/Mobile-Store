pipeline{
    agent any
    stages{
        stage('checkout the code from SCM'){
            steps{
                echo 'Checkout the code '
            }
        }
        stage('Build the project') {
            steps {
                echo 'Building the project'
                sh 'mvn clean install -DskipTests'
            }
        }
    }
}
