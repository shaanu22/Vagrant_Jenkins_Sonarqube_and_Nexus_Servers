# Provisioning Jenkins, Sonarqube, and Nexus VMs Using vagrant
Automating the setup of 3 machines: Jenkins, Sonarqube, and Nexus to facilitate testing complete CICD pipelines

The main setup scripts were created from this repo with minor modifications: https://github.com/devopshydclub/vprofile-project/tree/ci-jenkins/userdata

# Clone the files 

git clone https://github.com/shaanu22/Vagrantfile_for_Jenkins_Sonarqube_and_Nexus_Servers.git

# Run the below commands inside the download directory 
vagrant up 

# To access the machines:
- vagrant ssh jenkins
- vagrant ssh nexus 
- vargrant ssh sonar

# Machines' web ports: 
- jenkins http port is 8080 
- Sonarqube port is 9000 & 80 user/pass is : admin/admin
- nexus port 8081

# Disclaimer
Please note that while these scripts have been created with care, they are provided as-is, without any warranty or guarantee of performance. Use them at your own risk.
