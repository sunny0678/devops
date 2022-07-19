pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello'
        git(url: 'https://github.com/sunny0678/devops.git', branch: 'main', credentialsId: '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')
      }
    }

    stage('stage') {
      steps {
        tool 'gradle'
      }
    }

  }
}