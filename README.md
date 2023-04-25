The sample docker app will be deployed on the ubuntu host from the inventory file at defined port (http://35.177.208.114:3000/).

If you would like to deploy it on your own servers feel free to adjust variables in the inventory file and run the command:

`ansible-playbook -i inventory run.yml`

The project is working, if I had more time I would:
- fix the issue with mysql_db module on Amazon AMI
- make the nodejs app run as dedicated user (non root)
- make it compatible with RedHat/Centos systems
