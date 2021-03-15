@Library('My-Shared-Lib') _
log.info 'Starting'
log.warning 'Nothing to do!'

  def scm = new org.data.SCMScript()
  scm.checkOutFrom("SVN")
   
  echo "Using Point class to draw"
  def obj = new org.data.Point()
  data = obj.draw("Square")
  echo data
  buildMavenStep [user: 'Hp-User', repo: 'MavenWebApp']

