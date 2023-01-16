facts and history
===================----------------==================----------------------

Roles:
the role is the primary mechanism for breaking a playbook into multiple files
The breaking of playbook allows you to logically break the playbook into reusable components.
handlers:
tasks under this tag will run only when they are called by notify
using name tag.

and then change color accordingly.

a handler can have multiple tasks

role name = folder name

ansible-playbook setup.yaml
ansible-galaxy role -l
ansible-galaxy role init <roleName>
defaults  files  handlers  meta  README.md  tasks  templates  tests  vars

