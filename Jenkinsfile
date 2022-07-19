node('built-in') 
{
    stage('ContinuousDownload_Master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuousbuild_Master') 
	{
    sh label: '', script: 'mvn package'
	}
   }
