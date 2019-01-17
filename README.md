DOCKER-REGISTRY
=========

Requirements
------------

- CENTOS 7+

Role Variables
--------------

parameter | description
------------ | -------------
SRV_PATH | 配置目录
DOCKER_REGISTRY_USER | Docker仓库认证用户
DOCKER_REGISTRY_PASSWORD | Docker仓库认证密码


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: docker-registry }

License
-------

BSD
