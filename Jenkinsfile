pipeline {
  agent any
  stages {
    stage ("build") {
      steps {
        echo "etape #1 : build"
        sh 'echo PATH=$PATH'
        sh 'pwd'
        sh 'id'
      }
    }
    stage ("test") {
      steps {
        echo "etape #2 : tests de toutes sortes"
        sh 'ansible --version'
      }
    }
    stage ("deploy") {
      steps {
        echo "etape #3 : deploiement"
        sh 'ping -c5 192.168.1.61'
      }
    }
  }
}
