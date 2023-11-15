pipeline{
       
agent {

label{

      label "slave-1"
      
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

sh "sudo service https start" 
sh "sudo cp -r index.html /var/www/html/"
sh "sudo chmod -R 777 /var/www/html/"



}



}
}

}
