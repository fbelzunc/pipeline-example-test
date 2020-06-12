pipeline {
  agent {
    kubernetes {
    label 'fbelzunc-pod-template-without-jnlp'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPod.yaml'
    yamlMergeStrategy 'merge()'  
    }
  }
  
  stages {
      stage('Main') {
          steps {
              sh 'echo "Hello World!"'
              sh 'sleep 5'
          }
      }
    }
}
