# ec2-jenkins-installing
How to install jenkins on a linux EC2 machine. 


`sudo yum update –y`

` sudo wget -O /etc/yum.repos.d/jenkins.repo http://pkg.jenkinsci.org/redhat/jenkins.repo`

` sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io.key`

` sudo yum install jenkins -y`

` sudo service jenkins start`

After your Jenkins installed you need to enter administrator password. 

Password can be reach from ; 

` sudo cat /var/lib/jenkins/secrets/initialAdminPassword`

You can start writing nice pipelines :)
