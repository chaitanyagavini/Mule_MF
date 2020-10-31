pipeline
{
agent any
stages{
stage('Build Application'){
steps{
bat 'mvn clean install'
}
}
stage('Deploy Application')
{
steps{
bat 'mvn package deploy -DmuleDeploy -Dmule.home=C:/Users/cgavini/Downloads/mule-ee-distribution-standalone-4.3.0/mule-enterprise-standalone-4.3.0'
}
}
}
}