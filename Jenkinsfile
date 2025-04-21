pipeline {
    agent any

    stages {
        stage('Run Commands') {
            steps {
                echo 'Listing files...'
                sh 'ls'

                echo 'Printing current directory...'
                sh 'pwd'

                echo 'Showing current date and time...'
                sh 'date'

                echo 'new location'
                sh 'pwd'
            }
        }
    }
}
