ansible-vault decrypt my-vaulted-file --vault-id ~/.vault-joe90
ansible-vault encrypt my-vaulted-file --vault-id ~/.vault-joe90

ansible-vault encrypt_string 'some-password-of-your-choosing' --name 'snippets_password'

ansible-playbook -i inventory.yml playbook.yml