Follow The Above Steps:

1)Make sure Vagrant is installed locally and works.

2)Clone Repo --> https://github.com/tier5/Employee_Bhaskar.git

3)Issue the command --> vagrant box add ubuntu.16.04 https://cloud-images.ubuntu.com/xenial/current/xenial-server-cloudimg-i386-vagrant.box

4)Issue the command --> vagrant up

5)Issue the command --> vagrant ssh

6)Issue the command --> cd /var/www/html/scripts 

7)Issue the command --> sudo ./setup ( Make sure local mysql password should be toor )

8)Then Local Environment Can be Seen at --> http://127.0.0.1:5555
