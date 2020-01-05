stage('Build') {
   steps {
       echo 'Building...'
   }
   post {
       always {
           jiraSendBuildInfo branch: '*', site: 'elaks.atlassian.net'
       }
   }
}
