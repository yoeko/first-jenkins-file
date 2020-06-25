node{
  stage ('Build') {

    git url: 'https://github.com/yoeko/tp6maven.git'

    withMaven() {

      bat "mvn package"

    } // withMaven will discover the generated Maven artifacts, JUnit Surefire & FailSafe reports and FindBugs reports
  }
}
