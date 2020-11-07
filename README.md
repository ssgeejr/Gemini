# Gemini
Notes, ideas, scripts and testing for creating a dynamic hosts file

The hope is to creat a standard hostfile along with a new, ansible controlled hosts file and then cat them together. 

the basics: create /etc/hosts.d 
then create
/etc/hosts.d/local.conf
/etc/hosts.d/ansible.conf
and using a script, marry the two together: `cat /etc/hosts.d/local > /etc/hosts && cat /etc/hosts.d/ansible >> /etc/hosts`

