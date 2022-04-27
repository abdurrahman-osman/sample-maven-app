pipeline{
  agent any
  stages {
  stage('maven install') {
    steps {
         withMaven( maven: 'MyMaven'){
              sh 'mvn clean install'
          }
    }
  }

 }
}
