# mac-local-playbooks

This Ansible playbooks are for the initial setting of my local mac.

## setup beforehand
### 1. install homebrew

```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### 2. install git

```sh
brew install git
```

### 3. clone this repository

```sh
mkdir ~/Projects \
git clone https://github.com/HiromuMasuda/mac-local-playbooks.git
```

## run ansible

### 1. install ansible

```sh
brew install ansible
```

### 2. run ansible-playbooks command

```sh
cd ~/Projects/mac-local-playbooks \
ansible-playbook playbooks/initial_settings.yml
```

## setup details

1. vim
2. tmux
3. fish
4. python

