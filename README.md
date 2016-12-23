Ansible Role: PHP Memcached
===========================

Install PHP Memcached for PHP 5.6 or PHP 7.0

Requirements
------------

- PHP 5.6 or PHP 7.0

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

Dependencies
------------

- geerlingguy.memcached

Example Playbook
----------------

    - name: Install PHP Memcached
      hosts: all
      become: true
      become_method: sudo
      roles:
        - mosufy.php-memcached

License
-------

This codebase is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

Author Information
------------------

For any issues with installation or getting this to work, send an email to: [mosufy@gmail.com](mailto:mosufy@gmail.com)
