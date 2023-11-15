pipeline{
       
agent {

label{

      label "slave-2"
      
}

}

stages {

stage ('instal httpd') {

  steps {

        sh "sudo yum install httpd -y"

}
}

stage ('httpd start')
 {

steps{

sh "sudo service httpd start" 
sh "sudo cp -r index.html /var/www/html/"
sh "sudo chmod -R 777 /var/www/html/"



}



}
}

}
