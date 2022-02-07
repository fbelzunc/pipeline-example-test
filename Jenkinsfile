pipeline {
  agent {
    kubernetes {
    label 'fbelzunc-pod-template'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPod.yaml'
    }
  }
  
  stages_TODELETE {
      stage('Main') {
          steps {
              sh 'echo "Hello World!"'
          }
      }
    }
}
