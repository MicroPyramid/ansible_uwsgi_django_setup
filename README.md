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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      remote_user: root
      roles:
        - { role: micropyramid.uwsgi_django_setup, project_name: "your_project_name" }

License
-------

MIT

Author Information
------------------

Jagadeesh(jagadeesh@micropyramid.com), Dinesh(dinesh@micropyramid.com)
