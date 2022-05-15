pipeline{
    agent{
        label 'rhel_agent_1'
    }  
    stages {
        stage("checkout"){
            steps {
                checkout scm
            }
        }
            stage('Build'){
                steps{
                sh "mvn clean install"
            }  
        }
    }

}
