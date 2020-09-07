 pipeline {
    
    agent any
    

    stages {
        bat('Compile') {
            steps {
                echo "Compiling the Code.........."
              git credentialsId: 'Github-Details', url: 'https://github.com/shefalisardana/SampleJavaProject'
                bat "mvn compile"
            }
        }
        
        }
    }
