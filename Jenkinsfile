node {
   
   stage('preparation'){
      checkout scm
   }
   stage('test') {
      nodejs(nodeJSInstallationName: 'NodeJS8'){
          sh 'npm test'
       }
     }
}
         
       
