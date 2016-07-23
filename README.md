Role Name
=========

Collection of utils to get secrets from an S3 bucket

Requirements
------------

Requires Ansible 2.0 or higher.

Role Variables
--------------

* ansible_secrets_directory: The directory in which secrets are stored
* ansible_secrets_url: The S3 URL from which to download the file
* ansible_secrets_file: The filename in which the above secret is stored
* ansible_secrets_username: The username that owns the secret
* ansible_secrets_groupname: the groupname that owns the secret



Dependencies
------------

Probably docker :-)

Example Playbook
----------------

    - hosts: foo
      roles:
         - role: dieswaytoofast.ansible_weave

License
-------

BSD

Author Information
------------------

Mahesh Paolini-Subramanya (@dieswaytoofast)
