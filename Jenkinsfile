@Library('My-Shared-Lib') _
log.info 'Starting'
log.warning 'Nothing to do!'


node {
    stage("Hello World") {
        echoStep "Bava"
    }
}
  def scm = new org.data.SCMScript()
  scm.checkOutFrom("SVN")
  
  echo "Using Point class to draw"
  def obj = new org.data.Point()
  data = obj.draw("Square")
  echo data
  buildMavenStep(user: 'pbadhe34', repo: 'Maven-Spring-App')
  buildMavenStep(user: 'pbadhe34', repo: 'Maven-REST-Service')


  //invoke declataive pipeline
 

  declarativePipeline(currentBuild.getNumber())

