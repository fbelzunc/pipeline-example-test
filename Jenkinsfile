pipeline {
  agent {
    kubernetes {
    label 'default-java'
    defaultContainer 'jnlp'
    yamlFile 'pipeline/KubernetesPod.yaml'
    }
  }
  
  stages {
      stage('Main') {
          steps {
              sh 'echo "Hello World!!!!!!"'
          }
      }
    }
}
