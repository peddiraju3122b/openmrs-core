pipeline{
    agent{label 'JDK11'}
    stages{
        stage('clone'){
            steps{
                git url: 'https://github.com/peddiraju3122b/openmrs-core.git',
                branch:'master'
            }
        }
        stage('mvnbuild'){
            steps{
                sh 'mvn package'
            }
        }
    }
}   

    