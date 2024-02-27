pipeline {
  agent {
    kubernetes {
    label 'fbelzunc-pod-template-with-jnlp'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPod.yaml'
    }
  }
  
  stages {
      stage('Main') {
          steps {
              sh 'ls -la'
              sh 'echo Hello World!!!!!'
          }
      }
    }
}
