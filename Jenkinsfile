myVar = 'initial_value'
node {
stage('Build') {
  echo 'on branch production'
  echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
    echo " name is ${params.myname}"
  echo "var value is ${myVar}"
myVar = 'changed by build'
echo 'Building....'
}
 
stage('Test') {
echo 'Building....'
   echo "var value is ${myVar}"
}
stage('Deploy') {
echo 'Deploying....'
}
}
