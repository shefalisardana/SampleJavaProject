 pipeline {
    
    agent any
    

    stages {
        sh('Compile') {
            steps {
                echo "Compiling the Code.........."
              git credentialsId: 'Github-Details', url: 'https://github.com/shefalisardana/SampleJavaProject'
                bat "mvn compile"
            }
        }
        
        }
    }
