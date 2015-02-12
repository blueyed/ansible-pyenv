
[![Build Status](https://travis-ci.org/shogito/ansible-pyenv.svg?branch=master)](https://travis-ci.org/shogito/ansible-pyenv)

# Ansible Role: ansible-pyenv

### $BMW5a(B
$B$H$/$K$J$7(B

### Role Variables
pyenv$B$r%$%s%9%H!<%k$9$k%f!<%6(B
```
ANSIBLE_PYENV_PYENV_USER
```
pyenv$B$r%$%s%9%H!<%k$9$k%m%1!<%7%g%s(B
```
ANSIBLE_PYENV_PYTENV_USER_HOME
```
pyenv$B$G%$%s%9%H!<%k$9$k(BPython Version
```
ANSIBLE_PYENV_PYTHON_VERSION
```

### Example Playbook
```
- hosts: server
  vars:
    ANSIBLE_PYENV_PYENV_USER: root
	ANSIBLE_PYENV_PYENV_USER_HOME: /root 
	ANSIBLE_PYENV_PYTHON_VERSION: 2.7.9
  roles:
    - { role: shogito.ansible-pyenv }
```

### License
MIT / BSD

### Author Information

