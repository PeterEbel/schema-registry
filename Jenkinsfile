pipeline {
  agent any
  stages {
    stage('Pull Schema') {
      steps {
        git(url: 'https://github.com/PeterEbel/schema-registry', branch: 'main')
      }
    }

  }
}