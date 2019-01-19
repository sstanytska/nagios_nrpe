# nagios_nrpe

nrpe installtion on CentOS7 and Amazon-Linux

Steps:

Takes input for Nagios Server's IP
Installs epel-release repository on CentOS7 and Amazon-Linux
Installs nrpe and nrpe-plugins on specified hosts
Configures /etc/nagios/nrpe.cfg file (adds Server's IP to allowed hosts)
Restarts nrpe service on Amazon-Linux
Restarts nrpe service on CentOS7
*NOTE When you run the playbook, it takes input for the Nagios Server's IP. Enter your Server's IP address.
