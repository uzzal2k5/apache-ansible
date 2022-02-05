# apache-ansible
Automate Apache2 Server

fully automated script that will :

1. provision Apache web server
2. create and load a web page
3. run the web server
4. provide us with an IP address or URL to access the above.
5. Run a test to check if url is accessible.
6. Publish the test results
   Any improvisation in the process is a plus point.

Require a shell script as well as a ansible/terraform job for the same

Commands
---

ansible-playbook -i inventory.yml  apache.yml --extra-vars "node_group=webapplication"  --ask-become-pass