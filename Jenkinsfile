pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
                // Clonar repositorio git
                git 'https://github.com/cdchinchia/HelloWorld.git'
            }
        }

        stage('Build') {
            steps {
                // Ejecutar el programa Hello World en Python
                sh 'python3 HelloWorld.py'
            }
        }
    }
}
