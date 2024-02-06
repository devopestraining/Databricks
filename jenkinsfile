echo "Hello DB" 
node{
  stage('checkout'){
     
       git branch : 'main', credentialid:'9bb8e9a9-e81e-4931-89ee-792b427e58c0',
       url: 'https://github.com/devopestraining/Databricks.git'
        
  }
  stage('Build'){
     
       bat 'echo Hello Build stage'
        
  }
  stage('Deploy'){
     
       bat 'echo Hello deploy stage'
       bat 'C:\\Users\\m.eemjurumedu\\AppData\\Local\\Programs\\Python\\Python311\\Scripts\\databricks.exe workspace import_dir C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\Databricks\\jenkinstest /Shared/meenakshifolder'
        
  }
}
