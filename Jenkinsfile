node {
def mavenHome=tool name : "maven3.8.1"
stage ('checkoutCode')
{
git branch: 'development', credentialsId: '6030fba8-8568-4fcc-80c6-d74ceefc48b6', url: 'https://github.com/venkatesh9542/maven-web-application.git'

}
/*stage ('Build')
{
sh "mvn clean package"
}
stage ('sonarQubeReport')
{
sh "mvn sonar:sonar"
}
stage ('artifactuploadToNexus')
{
sh "${mavenHome}/bin/mvn deploy"
}
stage ('Deploy to Tomcat')
{
sshagent(['52216a23-191a-4af5-bb13-2b1d8b54fdb5']){
sh "scp -o StrictHostkeyChecking=no target/maven-web-application.war ec2-user@43.204.147.170:/opt/apache-tomcat-9.0.63/webapps/"}
}
*/

}
