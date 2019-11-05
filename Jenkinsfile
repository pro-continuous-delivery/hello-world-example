node('master') {
    // some block
    
    checkout scm

    stage('build') {
        // some block
        withMaven(jdk: 'Default JDK', maven: 'Default Maven') {
        // some block
            sh label: '', script: 'mvn clean install'
        }


    }
}
