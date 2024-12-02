# to install latest version of ansible
# sudo pip-3.11 install ansible

# ansible --version

# ansible -i servers all -e ansible_user=ec2-user -e ansible_password=DevOps321 -m ping
# Here servers is a file holding all the Ip of servers

# if we have only one or two server then no need to create file 
# ansible -i 172.31.22.64, all -e ansible_user=ec2-user -e ansible_password=DevOps321 -m ping
