pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   agent any
       stages {
           stage('Build') {
               steps {
                   // TODO: Build the application
                   sh './gradlew assemble'
               }
           }
           stage('Test') {
               steps {
                   // TODO: Run tests
                   sh './gradlew test'
               }
           }
       }
}
