\# ansible_docker_and_portainer_ubuntu_install <br />
\# ansible playbook to install docker and portainer in ubuntu 20.04 <br />
\# this ansible playbook assumes that you: <br />
\# (1) have the NOPASSWD auth at the remote node to execute commands otherwise please insert line <br />
\# "your_username" ALL=(ALL:ALL)       NOPASSWD: ALL" in /etc/sudoers.d <br />
\# (2) are running a fresh install of ubuntu 20.04 x86 vm <br />
\# (3) have opened port 9000 to your ubuntu vm <br />
\# the objectives/tasks of this ansible playbook: <br />
\# (1) install dependencies for docker and portainer installations <br />
\# (2) fecth docker gpg and initialise docker repos 
\# (3) install docker packages <br />
\# (4) test docker installation by executing docker hello world container <br />
\# (5) install portainer <br />
\# to access portainer and setup user account: <br />
\# (1) open your web browser <br />
\# (2) key in your vm ip address and open port 9000 in the web address field (eg. 10.0.0.01:9000)
