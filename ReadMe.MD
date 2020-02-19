1. Build the profiledetails project to the maven repos
2. Copy the jar file path on the local repo and define it as 
jarfilesource: <path of the profiledetails jar here>
jarfiledest: /opt/jboss/fuse/jboss-fuse-6.3.0.redhat-187/data/repository/com/sample/poc/fabric/profiledetails/1.19.17-SNAPSHOT
3. Run the vagrant up command 
4. login to both fuse-001.local and fuse-002.local to make sure the environments are up and running
5. run the command ansible-playbook -i host_ansible configuration.yml
6. run the command ansible-playbook -i host_dr dr.yml

