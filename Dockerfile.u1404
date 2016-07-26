# Docker file for UMD User Interface
#
FROM aaroc/ansiblecontainer:u14.04
MAINTAINER Bruce Becker <bbecker@csir.co.za>
WORKDIR /root/DevOps/Ansible
RUN ansible-playbook -c local -i /etc/ansible/hosts worker-nodes.yml --skip-tags="slack"
