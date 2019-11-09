# todo
- fix dotfiles/tasks/main.yml (.bashrc)

# before ansible-playbook running

```
# install homebrew
(https://qiita.com/pypypyo14/items/4bf3b8bd511b6e93c9f9)


# install ansible
brew install ansible

# install role from ansible-garaxy
ansible-galaxy install --roles-path ./roles geerlingguy.mas

# install git
brew install git

# clone this repository
git clone git@github.com:pypypyo14/mac-setup.git

```

# exec
```
ansible-playbook playbook.yml
```