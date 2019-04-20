pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }

}
post { 
success 
{
mail to:"kumar.devops52@gmail.com" subject:"SUCCESS: ${currentBuild.fullDisplayName}", body: "Hello Praneeth Job Success."
}
}
}
