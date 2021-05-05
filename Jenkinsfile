 pipeline { 
 agent { 
 label 'pipeline'
 }
  
 stages {
   
 stage ('checkout')
 {
 steps 
  { 
   checkout scm
    } 
 }
   
         
stage ('Example')
   {
  steps  { 
   echo "Hello, build example2" 
  }
   } 
 }
 }
