pipeline{
    agent any
    tools
    {
        maven "MAVEN"
    }
    stages
    {
        stage ("Checkout-git")
        {
            steps
            {
                git 'https://github.com/Charan-Samsani/petclinic_2.git'
            }
        }
    }
}
