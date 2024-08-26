pipeline {
    agent any /* { 
    triggers {
        pollSCM '* * * * *'
    } */
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                echo "Hii"
                echo "Added new Line For Test"
                echo "Build"
               /*  sh '''
                cd myapp
                pip install -r requirements.txt
                ''' */
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                /* sh '''
                cd myapp
                python3 hello.py
                python3 hello.py --name=Aniket
                ''' */
            }
        }
        stage('Deliver') {
            steps {
                echo "Deliver...."
                /* sh '''
                echo "doing delivery stuff.."
                ''' */
            }
        }
    }
}
