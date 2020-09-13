# pfsense ansible playbook 

Here is the upstream [ansible-pfsense](https://github.com/opoplawski/ansible-pfsense) the only change is adding tasks so this modules works
for me i had problems using ansible galaxy collections.

- Ansible variables ansible found in  [here](group_vars/all.json) 

- Task found [here](roles)

- master playbook found here [here](site.yml)


When running this playbook you must set the right number of [variables](group_vars/all.json)  to true
since i am using that to control how many of the modules in the tasks is going to be executed.

To run this playbook cd to dir and run 
```
ansible-playbook -i hosts site.yml
```

[master playbook](group_vars/all.json)  controls what tasks is going to run and what order
