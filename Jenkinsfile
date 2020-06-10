pipeline {
  agent {
    kubernetes {
    label 'fbelzunc-pod-template'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPos.yaml'
    }
  }
  
  stages {
      stage('Main') {
          steps {
              sh 'hostname'
          }
      }
    }
}
