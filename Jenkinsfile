pipeline {
  agent any
  stages{
    stage('Checkout'){
      steps{
        echo 'obteniendo el código desde GitHub...'
      }
    }
    stage('Compilación'){
      steps{
        bat 'javac Holamundo.java'
      }
    }
    stage('Ejecución'){
      steps{
        bat 'java Holamundo'
      }
    }
  }
}
  
