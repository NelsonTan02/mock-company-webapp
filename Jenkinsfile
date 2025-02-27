pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
   agent any
       stages {
           stage('Stage 1') {
               steps {
                   ./gradlew assemble
               }
           }
           stage('Stage 2'){
               steps{
                   ./gradlew test
               }
           }
       }
}
