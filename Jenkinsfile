pipeline {
  agent any
  stages {
    stage('runIt') {
      environment {
        projectName = 'Build1'
        serverDomainm = 'Build1 Server Domain'
      }
      steps {
        libraryResource 'demoPipeline'
      }
    }
  }
}