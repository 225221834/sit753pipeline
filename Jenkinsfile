pipeline{
   agent any
     stages {    
        stage('Build'){
           steps{
                // This show successful code build
                echo "Build the application completed successfully"
           }
          }
         // This show successful test
          stage('Test'){
               steps{
                echo "Run tests on the application completed successfully"
           }
          }
         // This show successful code quality
          stage('Code Quality'){
               steps{
                echo "Checking code quality completed successfully"
           }
          }
            // This show successful deployment
          stage('Deploy'){
               steps{
                echo "Code deployment of the application completed successfully"
           }
          }
         
    }
}
