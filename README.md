maxmind_geolitecity
===================

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-maxmind_geolitecity.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-maxmind_geolitecity)

Use this role to install the GeoLiteCity database from maxmind

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

The default set of variables defines the source and target for the maxmind GeoLiteCity database

    maxmind_path: /usr/share/GeoIP
    maxmind_url: http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz

Example Playbook
----------------

    - hosts: geolitecity
      roles:
      - { role: andrelohmann.maxmind_geolitecity }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
