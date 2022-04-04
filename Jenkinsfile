pipeline {
    agent any
    stages {
    stage('docker run') {
      steps {
        withDockerContainer(args: '--name nginx-container-create-by-jenkins -v /some/content:/usr/share/nginx/html:ro -d nginx', image: 'nginx') {
    // some block
}
      }
    }

  }
}
