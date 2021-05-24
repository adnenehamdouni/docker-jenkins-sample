node {
  stage 'Checkout'
  git url: 'https://github.com/adnenehamdouni/docker-jenkins-sample.git'

  stage 'build'
  docker.build('mobycounter')

  stage 'deploy'
  sh './deploy.sh'
}