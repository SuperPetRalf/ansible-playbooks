# ansible-playbooks

1. Changes the hostname, will ask for sudo password. Uses account "Christian Clarke"
    >ansible-playbook rename-pi-host.yaml -i 192.168.1.94, --extra-vars "hostname=picohost-" --private-key "~/Documents/home-key" --ask-become-pass
2.
