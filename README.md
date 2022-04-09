# ansible_and_vpn

ansible-playbook -i hosts ./playbook.yml -e @secrets_1.enc --vault-password-file ./password_file
nsible-galaxy init keepalived-slave 
ansible-vault edit ./secrets_1.enc
ansible-vault encrypt ./secrets.enc
