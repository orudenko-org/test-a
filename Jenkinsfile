pipeline {
  agent {
    docker 'nixos/nix:latest'
  }

  stages {
    stage('Hello') {
      steps {
        echo 'Hello A #1'
      }
    }
  }
}
