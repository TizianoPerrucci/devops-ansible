What's about:
=============

Here you can find some examples of Ansible playbooks.

* In `no-roles` there are simple playbooks.

* In `angular-spray-seed` there is a more complex example that uses roles and deploys StarterSquad client/server seed (*).


Once you made available of the VM listed in the `hosts` file, run the associated playbook:

`$ ansible-playbook -i hosts no-role/simple.yml -vv`

`$ ansible-playbook -i hosts no-role/ci.yml -vv`

`$ ansible-playbook -i hosts angular-spray-seed/site.yml -vv`


Presentation
============

Look into the `slides` directory if you are interested.



(*) Tested with Ansible 1.3.4