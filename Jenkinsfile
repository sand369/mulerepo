node {
stage('Check Out'){
git 'https://github.com/sand369/mulerepo.git'
}
stage('Compile'){
  def MVHome = tool name: 'Maven', type: 'maven'
  sh "${MVHome}/bin/mvn clean package"
}
}
