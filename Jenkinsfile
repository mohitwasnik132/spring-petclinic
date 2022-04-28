node ('MAVEN') {
  stage ('SCM'){
    //git clone
    git clone 'https://github.com/mohitwasnik132/spring-petclinic.git'
  }

    stage ('BUILD'){
    //mavn package
    sh 'mvn package'
  }

    stage ('archival'){
    //archive the artifact
    archieve 'target/*.jar'
  }
}