node {
   
   stage('preparation'){
      checkout scm
      }
   
   stage('install'){
      nodejs(nodeJSInstallationName: 'NodeJS9'){
        sh 'npm install'
       }
     }
   
   stage('test') {
      nodejs(nodeJSInstallationName: 'NodeJS9'){
          sh 'npm test'
       }
     }
}
         
       
