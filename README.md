andrewrothstein.kubernetes_helm
=========
![Build Status](https://github.com/andrewrothstein/ansible-kubernetes_helm/actions/workflows/build.yml/badge.svg)

Installs Kubernetes [Helm](https://helm.sh)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.kubernetes_helm
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein andrew.rothstein@gmail.com
