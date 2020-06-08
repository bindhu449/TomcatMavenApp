pipeline{
   agent any
   tools {
      maven 'MAVEN'
      jdk 'java'
   }
   stages {
    stage ('build')
      {
      steps {
      echo "building a maven project"
         sh 'mvn compile'
      }

}  
 stage ('test')
      {
      steps {
      echo "testing"
         sh 'mvn test'
      }

}  

 stage ('deploy')
      {
      steps {
      echo "dploting"
         sh 'mvn deploy'
      }

}  

}

}
