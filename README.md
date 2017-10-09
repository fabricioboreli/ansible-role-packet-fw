Ansible Role Packet FW
======================
Ansible role para ativar _packet forwarding_ para ipv4 no kernel linux via sysctl.

Requisitos
----------
Nenhum

Variaveis do Role
-----------------
Nenhuma variavel

Dependências
------------
Não depende de nenhum outro role.

Playbook de exemplo
-------------------
```yaml
- name: Role name
  hosts: server
  become: true
  gather_facts: true

  roles:
    - role: ansible-role-packet-fw
```

TODO
----
- Adicionar suporte a ipv6.

Licença
-------
MIT

Informações do Autor
--------------------
Fabricio Boreli Ferreira  
fabricioboreli at openmailbox dot org  
