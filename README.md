
This a repository created for network assignment

It deploys a docker container running apache service on specified subnet 172.168.10.0/30

Install two Virtual machines runing ansible in one host and docker in the other host.

Make sure ansible hosts file is been updated to perform the automation.  

The given playbook has been updated with all necessary details to deploy the apache container hosting static webpage.

In this playbook I have used podman docker.So if you are using docker make sure to change the docker service state as docker in the playbook file.

Run the playbook and confirm the webpage by navigating to the IP address of the container.

  
