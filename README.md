# Synthetic Ping Using Ansible
Using Ansible to run ping test
Command:
probeName=CHELSEA probeLocation=Alex ansible-playbook ping_probe.yml -e "hosts='facebook.com google.com' workspace=."

Requirements:
1. Copy this python code 'https://gist.github.com/ageis/face10be67b26e4519662e19290e06ff' into net_tools directory '/usr/lib/python2.7/site-packages/ansible/modules/net_tools/icmp_ping.py'
2. Python package 'netifaces'
