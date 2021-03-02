pipeline{

  node any
  
  stages {
  
  
    stage('Pull code'){
    
      steps{
      
        sh ''' #/bin/bash -ex
             apt-get update && apt install git     
      
      } // end steps
    } // end pull code stage
    
  } // end stages
post{
 always{
 print(env.BUILD_STATUS) 
 }

}

} // end pipeline
