@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
	
  stage('apiProxyList Command') {
      setupCommonPipelineEnvironment script: this
      print "api Proxy List:" 
     apiProxyList script: this
     print  commonPipelineEnvironment.getValue("custom/apiProxyList")	  
  }
}
