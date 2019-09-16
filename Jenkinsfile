myVar = 'initial_value'
node {
stage('Build') {
  echo 'on branch production'
    echo " name is ${params.myname}"
  echo "var value is ${myvar}"
myvar="changed by build"
echo 'Building....'
}
 
stage('Test') {
echo 'Building....'
   echo "var value is ${myvar}"
}
stage('Deploy') {
echo 'Deploying....'
}
}
