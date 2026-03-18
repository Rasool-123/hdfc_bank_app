pipeline {
    agent any
    
    tools{
        maven 'maven-3.9.13'
    }
    stages {
        stage('clone') {
            steps {
              git 'https://github.com/ashokitschool/maven-web-app.git'
            }
        }
        stage('build'){
            steps{
                 sh 'mvn clean package'
            }
        }
       
        
    }
}
