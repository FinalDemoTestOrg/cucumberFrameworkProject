pipeline{
    
            agent any
            stages{
                stage('checkout'){
                    
                    steps{
                            echo "code checkout"
                           git branch: 'firstbranch', url: 'https://github.com/FinalDemoTestOrg/cucumberFrameworkProject.git'
                    }
                
                
                }
                stage('test'){
                    
                    steps{
                            echo "code test"
                            bat   "mvn test"
                    }
                
                
                }
                
            }    
                
}
        
    
    
    
    
    
