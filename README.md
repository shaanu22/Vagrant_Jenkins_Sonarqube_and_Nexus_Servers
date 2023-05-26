# Jenkins SonarQube Nexus vagrant-ubuntu
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

# Machnies web ports 
- jenkins http port is 8080 
- Sonarqube port is 9000 user/pass is : admin/admin

