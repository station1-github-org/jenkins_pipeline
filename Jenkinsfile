node {
   stage 'Stage 1'
   		echo 'Hello World 1'
   stage 'Stage 2'
   		echo 'Hello World 2'
   if (env.BRANCH_NAME == 'master') {
      build '../jenkins_pipeline_new/master'
   }
}
