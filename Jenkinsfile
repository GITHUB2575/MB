node('master') 
{
    stage('Continuous Download_Loans') 
	{
    git 'https://github.com/GITHUB2575/MB.git'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
