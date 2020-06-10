pipeline {
  agent {
    kubernetes {
    label 'fbelzunc-pod-template-without-jnlp'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPod.yaml'
    }
  }
  
  stages {
      stage('Main') {
          steps {
              sh 'echo "Hello World!"'
          }
      }
    }
}
