# Up a new system (OSX) in a few minutes

Install `Brew`:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install and run `Ansible`:

```bash
brew install ansible
ansible-galaxy collection install community.general
ansible-playbook setup.yml --ask-become-pass
```
