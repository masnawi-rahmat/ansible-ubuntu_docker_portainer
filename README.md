# ansible-ubuntu_docker_portainer
# ansible playbook to install docker and portainer in ubuntu 20.04
# this ansible playbook assumes that you:
# (1) have the NOPASSWD auth at the remote node to execute commands otherwise please insert line 
# "your_username" ALL=(ALL:ALL)       NOPASSWD: ALL" in /etc/sudoers.d
# (2) are running a fresh install of ubuntu 20.04 vm
# (3) have opened port 9000 to your ubuntu vm
# the objectives/tasks of this ansible playbook:
# (1) install dependencies for docker and portainer installations
# (2) fecth docker gpg and initialise docker repos
# (3) install docker packages
# (4) test docker installation by executing docker hello world container
# (5) install portainer
# to access portainer and setup user account:
# (1) open your web browser
# (2) key in your vm ip address and open port 9000 in the web address field (eg. 10.0.0.01:9000)
