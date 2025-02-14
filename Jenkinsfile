pipeline{
    
    tools{
        maven 'mymaven'
    }
   // in agent any = any available server 
    agent any
   stages{
       stage('Clone a Repo'){
           steps{
               git 'https://github.com/Sonal0409/DevOpsCodeDemo.git'
           }
       }
   }
}
