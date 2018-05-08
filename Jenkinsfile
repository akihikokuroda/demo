#!groovy

@Library('MicroserviceBuilder') _
microserviceBuilderPipeline {
  image = 'demo'
  test = 'true'
  mvnCommands = '-Dmaven.test.skip=true -DskipITs package'
  // mavenImage = 'dcurrie/maven-cache:3.5.2-jdk-8'
}
