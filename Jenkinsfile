pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/Neeraja037/StarAgile_HealthCare-Project.git'
        sh 'mvn -Dmaven.test.failure.ignore=true clean package'
      }
    }
  }
}
