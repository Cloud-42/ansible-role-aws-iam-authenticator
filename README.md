Role Name
=========

Installs aws-iam-authenticator used for IAM auth with EKS.

Description
-----------

Basic role to download and install the aws-iam-authenticator.

Role Variables
--------------

| Variable | Meaning |
| :------- | :----- |
| aws\_iam\_authenticator\_checksum | Binary checksum |
| tmp\_directory | TMP directory where binary is downloaded to |
| owner | Owner |
| group | Group to own file |

Example Playbook
----------------
    
    - hosts: servers
      roles:
         - aws-iam-authenticator 

License
-------

BSD

Author Information
------------------

Cloud 42 ( hello@cloud42.io )
