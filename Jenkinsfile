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
              sh 'echo "Hello World!. We are trying to trigger a Jenkins job with WebHook configured."'
          }
      }
    }
}
