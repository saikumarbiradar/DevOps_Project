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
                sh ''' echo "This is saikumar
                       sleep 10
                       date +%d-%m%y '''
            }
        }
    }
    
}
