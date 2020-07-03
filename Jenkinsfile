@Library('pipeline-library-demo')_

def app = "${params.app}"
node {
  stage('Build'){
       echo 'Build succeeded'
  }
  stage('Deploy'){
    deploy app
  }
}
