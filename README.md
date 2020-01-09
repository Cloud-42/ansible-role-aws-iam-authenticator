<p align="center">
  <a href="https://www.cloud42.io/" target="_blank" rel="Homepage">
  <img width="200" height="200" src="https://www.cloud42.io/wp-content/uploads/2020/01/transparent_small.png">
  </a>
</p>

---
<p align="center">Need help with your Cloud builds <a href="https://www.cloud42.io/contact/" target="_blank" rel="ContactUS"> DROP US A LINE</a>.</p>

---
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
