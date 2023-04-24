The sample docker app is deployed on the host from the inventory file at defined port (http://35.177.208.114:3000/).

If you would like to deploy it on your own servers feel free to adjust variables in the inventory file and run the command:

ansible-playbook -i inventory run.yml
