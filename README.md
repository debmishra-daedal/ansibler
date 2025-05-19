# ansibler
Uses ansible to remotely execute tasks across your platforms
# Note
- Remember to install ansible-core, ansible-lint and ansible-glaxy collection install community.general in node systems
- Ensure that the remote machines can be connected via ssh from node, before starting process
- Always have the vault_pass.txt in the .ansible folder of the project root. Set the mode to 600.
- Run ansible-galaxy collection install -r requirements.yml -p ./collections
