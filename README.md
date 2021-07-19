- [About](#about)
- [Installation](#installation)
- [Defaults](#defaults)

# About

This role is a modified version of Jeff Geerlings [`ansible-role-docker_arm`](https://github.com/geerlingguy/ansible-role-docker_arm). 

# Installation

Add the following to `requirements.yml`:

```
- src: git@gitlab.com:carbonique/ansible-role-docker-arm.git
  scm: git
  name: docker-arm
  version: #Leave empty for latest. To download a specific version: use the tag as listed in repo
```

For system wide installation:
`ansible-galaxy install -r requirements.yml`

For installation to the current directory:
`ansible-galaxy install --roles-path . -r requirements.yml`

# Defaults

Defaults have been prefilled.

For defaults see: `defaults/main.yml`

