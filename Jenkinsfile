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
                 stage('Publish Report'){
                    
                    steps{
                            echo "Report Publish"
                           cucumber failedFeaturesNumber: -1, failedScenariosNumber: -1, failedStepsNumber: -1, fileIncludePattern: 'Cucumber.json', jsonReportDirectory: 'C:\\Users\\Lenovo\\.jenkins\\workspace\\Jenkins-Pipeline-Job\\target\\cucumber-reports', pendingStepsNumber: -1, reportTitle: 'CucumberPipelineReports', skippedStepsNumber: -1, sortingMethod: 'ALPHABETICAL', undefinedStepsNumber: -1
                    }
                
                
                }
                
            }    
                
}
        
    
    
    
    
    
