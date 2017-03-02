Role Name
=========

Configure Ossec Server service

Requirements
------------

None

Role Variables
--------------

- ossec_email_notification: Ossec email notification activation. Default value:'yes'
- ossec_email_to: Ossec email to value. Default value:antonio.barbaro@gmail.com
- ossec_smtp_server: smtp server address value. Default value:localhost
- ossec_email_from: Ossec email from value. Default value:ossec@smartblot.com
- ossec_email_alert_level:: Ossec email notification alert level. Default value:8


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ossec-server

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
