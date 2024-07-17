pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
	
	stages{
		stage('Build'){
			./gradlew assemble
		}
		
		stage('Test'){
			./gradlew test

		}
	}

}
