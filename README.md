Role Name
=========

uwsgi_django_setup

Requirements
------------

Pre-created Django project over Ubuntu server.

Role Variables
--------------

vassals_dir: /etc/uwsgi/vassals
supervisor_conf_dir: /etc/supervisor/conf.d


Dependencies
------------

- { role: micropyramid.uwsgi }

Example Playbook
----------------

    - hosts: servers
      remote_user: root
      roles:
        - { role: micropyramid.uwsgi_django_setup, project_name: "your_project_name" }

License
-------

MIT
