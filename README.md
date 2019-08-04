Role Name
=========

Role destinada a instalar e configurar o **Prometheus Node Exporter** no CentOS 7.x

Role Variables
--------------

Esta role utiliza as variáveis abaixo:
```  
  node_exporter_version: 0.18.1
  node_exporter_port: 9100
  hash_node_exporter: b2503fd932f85f4e5baf161268854bf5d22001869b84f00fd2d1f57b51b72424
```

> Os valores acima serão usados por default.

Example Playbook
----------------

Como utilizar essa role na sua playbook:

    - hosts: all
      roles:
         - linux_node_exporter

License
-------

BSD

Author Information
------------------

LinkedIn: https://br.linkedin.com/in/ewertonsilva00
