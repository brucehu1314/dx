pipeline {
  agent any
  stages {
    stage('pull code') {
      steps {
        build(job: 'test01', propagate: true, quietPeriod: 60)
      }
    }

  }
}