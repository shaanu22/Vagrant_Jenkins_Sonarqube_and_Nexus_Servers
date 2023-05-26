# Jenkins SonarQube Nexus vagrant machines
This is setup for 3 machines Nexus , Sonarqube , Jenkins 
this will facilitate testing complete pipelines 

# download the files 

git clone https://github.com/omarfadl/jenkins-Sonar-Nexus-vagrant-ubuntu.git

# run the below commands in side the download directory 
vagrant up 

# to access the machines 
- vagrant ssh jenkins
- vagrant ssh nexus 
- vargrant ssh sonar

# Machines web ports 
- jenkins http port is 8080 
- Sonarqube port is 9000 & 80 user/pass is : admin/admin

# Disclaimer
Please note that while these scripts have been created with care, they are provided as-is, without any warranty or guarantee of performance. Use them at your own risk.
