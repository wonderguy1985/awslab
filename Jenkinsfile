node {
   def mvnHome
   stage('Preparation') { 
      sh 'echo perparation'
   }
   stage('Build') {
      // Run the maven build
      sh '/usr/local/bin/packer build -var aws_access_key=$aws_access_key ./aws2.json'
   }
   stage('Results') {
      sh 'echo finish'
   }
}
