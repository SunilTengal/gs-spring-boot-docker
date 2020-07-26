node{
stage ('scm checkout') {
git ('https://github.com/SunilTengal/gs-spring-boot-docker.git')
}

stage ('docker image build') {
sh 'mvn clean install dockerfile:build '
}

}

