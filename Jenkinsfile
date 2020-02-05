pipeline{
agent any
stages{

stage('Jenkins job'){
 steps {
 sh '''
 curl -X GET \
  http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/api/2/project/SMA \
  -H 'cache-control: no-cache' 
 '''
 }
 }
 }
 }
