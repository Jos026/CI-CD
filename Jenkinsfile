pipeline {
    agent any

    stages {
        stage("stage1") {
            steps {
                echo "Tarea 1"
                echo "Por Josue Ocampo"
            }
        }
        stage('stage2') {
            steps {
                echo "executing Tarea 1"
                sh "python hello-world.py"
            }
        }
        stage('stage3') {
            steps {
                echo "Success"
            }
        }
        
    }
}
