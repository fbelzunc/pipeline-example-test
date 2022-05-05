pipeline {
  agent {
    kubernetes {
    label 'defauilt-java'
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
