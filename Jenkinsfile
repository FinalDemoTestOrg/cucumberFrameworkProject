pipeline{
    
            agent any
            stages{
                stage('checkout'){
                    
                    steps{
                            echo "code checkout"
                            git branch: 'main', url: 'https://github.com/yashashree07/jenkinsfiletesting.git'
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
        
    
    
    
    
    
