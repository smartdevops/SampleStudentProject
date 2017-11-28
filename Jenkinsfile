env.dockerimagename="devopsbasservice/buildonframework:buildonJenkinsfile2.0"
node {
   stage ('BuildOn_Build') {
    checkout scm
    sh 'mvn clean package -DskipTests=True'
  } 
 //Test Buildon  Test github
}
