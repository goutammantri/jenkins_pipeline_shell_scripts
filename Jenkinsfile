node {
   
   	stage 'Stage 1'
   		echo 'Hello there, shell scripts'
   	stage 'Checkout'
   		git 'https://github.com/goutammantri/jenkins_pipeline_shell_scripts.git'
   	stage 'Build'
   		sh './myBuild.sh'
   	stage 'Deploy'
   		sh './myDeployment.sh'
  
}
