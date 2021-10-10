node('master') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/GITHUB2575/MB.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	}
}
