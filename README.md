Role: cns.efs
========

Ansible role to create EFS / NFS auto_share script, mount shares based on environment, and cron job to remount share if disconnected.

Requirements
------------

Debian 8.*

Role Variables
--------------

In the current version, you can specify the following variables:

| Name | Default |   |
|------|---------|---|
| efs_server_stage  |   ---   | EFS host (stage) |
| efs_server_prod  |   ---   | EFS host (prod) |

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

* Sam Morrison
