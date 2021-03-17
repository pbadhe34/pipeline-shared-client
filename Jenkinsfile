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
  //buildMavenStep(user: 'pbadhe34', repo: 'Maven-Spring-App')
 // buildMavenStep(user: 'pbadhe34', repo: 'Maven-REST-Service')


  //invoke declataive pipeline
 

 // declarativePipeline(currentBuild.getNumber())

  def get = new URL("http://localhost:8080/Spring-rest-service/person/3").openConnection();
def getRC = get.getResponseCode();
println(getRC);
if(getRC.equals(200)) {    
  res = get.getInputStream().getText()
    
//def output = new JsonSlurper().parseText( res )
    obj = com.data.JSONFileReader()
   output = ob.readJSONTreeData("/home/dell/jsondata.json")
// Print them out to make sure
//output.each { println it }
println output
}
