pipeline {
  agent {
    kubernetes {
    label 'fbelzunc-pod-template'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPod.yaml'
    }
  }
  
  stages {
      stage('Main') {
          steps {
              sh 'ls -la'
          }
      }
    }
}
