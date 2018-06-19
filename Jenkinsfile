pipeline {
  agent any
  stages {
    stage('buildIPA') {
      steps {
        sh '''if [ ${DEBUG_BUILD_SCRIPT} = "true" ] ; then
  set -x # Print all commands before running them
fi
'''
      }
    }
  }
}