node('built-in') 
{
    stage('Continuous Download_cards') 
	{
    git 'https://github.com/aslamzaeedGIT/mycode.git'
	}
    stage('Continuous Build_cards') 
	{
    sh label: '', script: 'mvn package'
	}
}
