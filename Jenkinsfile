pipeline {
      agent any

      stages {
            stage("Complie"){
              steps{
                  bat 'javac HelloWorld.java'
              }
            }
            stage("Run"){
              steps{
                  bat 'java HelloWorld'
              }
            }
      }
}
