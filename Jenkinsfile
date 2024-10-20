pipeline {
  agent any
  stages{
    stage("build"){
      steps{
      bat "javac Demo.java"
    }
    }
    stage("run"){
      steps{
        bat "java Demo"
      }
    }
  }
}
    
