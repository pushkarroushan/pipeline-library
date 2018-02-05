@Library('pipeline-library')
import politie.jenkins.*

def builder = new JenkinsPipelineBootstrap().createBuilder()

String serviceName = 'my-service'
String gitBranch = 'master'

builder.mavenApplicationPipeline(serviceName, gitBranch) 
