node{
   stage('preparation'){
      checkout scm
      }
   stage('install'){
      nodejs(nodeJSInstallationName: 'NodeJS9'){
        sh 'npm install --only=dev'
       }
     }
   stage('test') {
      nodejs(nodeJSInstallationName: 'NodeJS9'){
          sh 'npm test'
       }
     }
}
         
       
