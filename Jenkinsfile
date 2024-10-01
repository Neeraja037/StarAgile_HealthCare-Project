pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        // Get some code from a Github repository
        git "https://github.com/Neeraja037/StarAgile_HealthCare-Project.git"

        // Run Maven on a Unix agent.
        sh "mvn -Dmaven.test.failure.ignore=true clean package"

      }
    }
  }
}
