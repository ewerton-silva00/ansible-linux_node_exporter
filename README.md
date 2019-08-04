Role Name
=========

Role destinada a instalar e configurar o **Prometheus Node Exporter** no CentOS 7.x

Role Variables
--------------

Esta role utiliza as variáveis abaixo:
```  
# Versão do Node Exporter.
node_exporter_version: 0.18.1

# Porta TCP a ser utilizada.
node_exporter_port: 9100

# Hash SHA256 disponível em https://prometheus.io/download/
# A hash precisa corresponder a versão do Node Exporter a ser instalado.
node_exporter_hash: b2503fd932f85f4e5baf161268854bf5d22001869b84f00fd2d1f57b51b72424

# Usuário que será criado para execução do serviço node_exporter.service
node_exporter_user: exporter
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
