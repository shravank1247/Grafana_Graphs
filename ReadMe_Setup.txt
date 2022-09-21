	1. C:\Avocet\DataArchival\New\Grafana-master ….. Use below zip of grfana to run 
	
	
	2. Copy this floder into linux machine
	3. Execute : docker-compose -f ./Grafana-mster/docker-compose.yml up (add -d if detach mode )
	4. Run this cmd in local machine:::
		a. ssh -L local_port:destination_server_ip:remote_port ssh_server_hostname
		b. Eg:  ssh -L 3000:10.21.1.15:3000 avocetadmin@10.21.1.15
	5. For dashboard Browse to : localhost:3000 
Below is the customised dashboard for docker DA