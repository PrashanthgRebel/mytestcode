pipeline {
    agent any
        tools{
            maven 'maven3'
        }

        stages {
            stage('welcome'){
                steps{
                    echo "welcome to jenkins practice"
                    git branch: 'main', url: 'https://github.com/PrashanthgRebel/mytestcode.git'
                }

            }

            

        }
