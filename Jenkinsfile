pipeline{
    agent any
    parameters{
        choice(name:'Environment', choices:['QA1','QA2','QA3','QA6'], description:'Select Run Environment')
    }
    stages{
        stage("build"){
            steps {
                //Scripts to execute some commands in Jenkins server
                echo 'building the application'
            }
        }
        stage("test"){
            steps {
                //Scripts to execute some commands in Jenkins server
                echo 'testing the application'
            }
        }
        stage("deploy"){
            steps {
                //Scripts to execute some commands in Jenkins server
                echo 'deploying the application'
            }
        }
    }
}