# nagios_nrpe

nrpe installtion on CentOS7 and Amazon-Linux

Steps:

1. Takes input for Nagios Server's IP
2. Installs epel-release repository on CentOS7 and Amazon-Linux
3. Installs nrpe and nrpe-plugins on specified hosts
4. Configures /etc/nagios/nrpe.cfg file (adds Server's IP to allowed hosts)
5. Restarts nrpe service on Amazon-Linux
6. Restarts nrpe service on CentOS7
*NOTE When you run the playbook, it takes input for the Nagios Server's IP. Enter your Server's IP address.
