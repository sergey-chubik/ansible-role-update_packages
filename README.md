Ansible Role: Install/Update packages
=========

Эта роль установит или обновит до последней версии програмное обеспечение ОС Linux (RedHat/Debian). Если доступ к репозиториям с програмным обеспечением осуществляется через Proxy-сервер, то роль настроит менеджер управления зависимостями (пакетами) для работы через Proxy-сервер.

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены ниже вместе со значениями по умолчанию в файле **defaults/main.yml**.
Настройка работы менеджер управления зависимостями (пакетами) через Proxy-сервер (по умолчанию `false`)
```
update_packages_set_proxy: false
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - update_packages

License
-------

BSD

Author Information
------------------

Chubik Sergey.
