Ansible role ses-notification
=========
Ansible role that sends email using aws command line tool and ses service

Requirements
------------
AWS cli is required.

Role Variables
--------------
- `email` - sets To email address
- `subject` - sets email subject
- `body` - sets text email message

Dependencies
------------

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: ses-notification,
                email: <email>
                subject: <subject>
                body: <message>
           }

License
-------
MIT/BSD
