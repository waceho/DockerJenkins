node {
   
   stage('preparation'){
      checkout scm
   }
   
   stage('install') {
      nodejs(nodeJSInstallationName: 'NodeJS8'){
          sh 'npm install'
       }
     }
   
   stage('test') {
      nodejs(nodeJSInstallationName: 'NodeJS8'){
          sh 'npm test'
       }
     }
}
         
       
