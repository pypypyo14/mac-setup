# before ansible-playbook running

```
# install homebrew
(https://brew.sh/index_ja)

# install ansible
brew install ansible

# clone this repository
git clone git@github.com:pypypyo14/mac-setup.git && cd mac-setup

# install role from ansible-garaxy
ansible-galaxy install --roles-path ./roles geerlingguy.mas

```

# exec
```
ansible-playbook playbook.yml -K
```