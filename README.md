ansible role for installing node_exporter on Ubuntu and CentOS systems creating a systemd service that can be start/stopped/enabled.

To run, clone repo with ansible installed, and run:

echo "localhost" > hosts && ansible-playbook -i hosts site.yml --private-key ~/.ssh/id_rsa

Replace localhost with your target IP and ~/.ssh/id_rsa with your ssh key
