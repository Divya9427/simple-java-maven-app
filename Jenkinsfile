pipeline {
    agent any
    stages {
        stage ('Compile') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                    sh 'mvn clean package'
                }
            }
        }
       //post {
       //always {
            //archiveArtifacts artifacts: 'build/libs/**/*.jar', fingerprint: true
           //junit 'target/surefire-reports/*.xml'
            //archive "target/**/*"
         //   junit '/var/lib/jenkins/workspace/pipeline_multibranch_divya/target/surefire-reports/*.xml'
            
      // }
       //}
     }
}
