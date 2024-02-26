pipeline {
  agent any
  stages
   {
         stage("GIT")
	 {
           steps
		{
		git "https://github.com/Lalit280/feb26_task.git"
		}
	 }
	 stage("RUN")
         {
           steps
		{
		sh "java Demo.java"
		sh "python3 main.py"
		}
	 }
   }
}i
