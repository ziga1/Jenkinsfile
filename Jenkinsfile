pipeline {
    agent any

    stages {
        stage('Print message') {
            steps {
                sh 'javac Main.java'  // Compile the Java code
                sh 'java Main'        // Run the compiled Java program
            }
        }
    }
}
