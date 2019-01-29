node {
stage('Check Out'){
checkout scm
}
stage('Compile'){
  def MVHome = tool name: 'Maven', type: 'maven'
  sh "${MVHome}/bin/mvn clean package"
}
}
