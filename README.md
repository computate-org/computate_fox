
# Install the fox ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_fox

# Clone the fox ansible role. 
git clone git@github.com:computate-org/computate_fox.git ~/.ansible/roles/computate.computate_fox

# Change into the fox ansible role directory. 
cd ~/.ansible/roles/computate.computate_fox
```

# Run the fox ansible playbook to install fox locally. 

```bash
ansible-playbook install.yml
```

