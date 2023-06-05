@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
	
  stage('apiProxyList Command') {
	
	apiProxyList script: this
  }
}
