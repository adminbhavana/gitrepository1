pipeline{
 agent any
 stages{
   stage('Fetch code'){
    steps{
      git branch:'master', url:'https://github.com/adminbhavana/gitrepository1.git'
    }
   }
   stage('Build'){
    steps{
     sh 'mvn install'
    }
   }
   stage('Test'){
    steps{
     sh 'mvn test'
    }
   }
 }
}
