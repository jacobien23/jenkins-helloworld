node {
    stage('clone') {
      git 'https://github.com/jacobien23/jenkins-helloworld.git'   
    }
   stage('build') {
  
   sh '''
         javac Main.java
          '''
}
stage('run'){
 sh '''
        java Main
        '''   
}
}
