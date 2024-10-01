pipeline {
  agent any
  
  stages {
    stage('build the project') {
      steps {
        git 'https://github.com/Neeraja037/StarAgile_HealthCare-Project.git'
        sh 'mvn clean package'
      }
    }
  }
}
