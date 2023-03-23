pipeline{
    agent any
    stages{
        stage( 'Git Checkout' ){
            steps{
                git branch: 'main', url: 'https://github.com/saikumarbiradar/DevOps_Project.git'
            }
        }
        stage( 'build' ){
            steps{
                sh "date +%d-%m-%y" 
            }
        }
    }
    
}
