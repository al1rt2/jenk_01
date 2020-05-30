pipeline {
  agent any
  stages {
    stage ("build") {
      steps {
        echo "etape #1 : build"
        sh 'echo PATH=$PATH'
        sh 'pwd'
        sh 'id'
        sh 'ansible --version'
      }
    }
    stage ("test") {
      steps {
        echo "etape #2 : tests de toutes sortes"
      }
    }
    stage ("deploy") {
      steps {
        echo "etape #3 : deploiement"
      }
    }
  }
}
