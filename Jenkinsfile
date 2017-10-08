node('master'){
stages {
     stage('Build') {
             echo 'Checkout SCM code'
             giturl="https://github.com/ojtjdevops/maven.git"
             git branch: "master", credentialsId: '032b2056-8289-42e8-a2b0-6f549f009f9d', poll: false, url: "${giturl}"
     
         }
    }
}
