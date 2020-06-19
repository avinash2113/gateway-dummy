pipeline
{
    agent {
        label 'master'


    }


	stages
	{


        stage("hello world")
        {
            agent
            {
                label "master"
            }
            steps
            {
                checkout scm
                sh "chmod +x print.sh"
                sh ". print.sh"



            }
        }

    }
}