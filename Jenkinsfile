myVar = 'initial_value'
node {
stage('Build') {
  echo 'on branch production'
    echo " name is ${params.myname}"
  echo "var value is ${myVar}"
myvar= 'changed by build'
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
