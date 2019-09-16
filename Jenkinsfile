node {
stage('Build') {
  echo 'on branch production'
echo 'Building....'
}
try{
        stage('to be failed')
  {
            %ERRORLEVEL%  =1
   }
    } 
  catch(e) 
  {     build_ok = false
        echo e.toString()  
    }
  
stage('Test') {
echo 'Building....'
}
stage('Deploy') {
echo 'Deploying....'
}
}
