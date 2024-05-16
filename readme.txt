# Powershell commands to work with a linux remote server

ssh himanshu@64.227.185.66 : To connect to a remote server
pwd : Present Working Directory
ls : List all the files and directories at a particular path
ls -lart : List all the files and folders including hidden files and folders
cd : Change directory

scp C:\Users\amazi\.ssh\id_rsa.pub himanshu@64.227.185.66:~/.ssh/authorized_keys

sudo vim index.html - Command to edit the index.html inside the Powershell
sudo service apache2 restart - Command to restart the apache2 service

sudo htop - Gives the Task Manager type result from the linux server inside the powershell window

# References

1: Setting up hosting server on digital ocean: 
    https://www.codewithharry.com/blogpost/setup-ubuntu-20-04-server/
2: Setting up SSH for passwordless connectivity with server: 
    https://www.codewithharry.com/blogpost/transferring-files-passwordless-login-ubuntu-20-04/
3: Installing LAMP(Linux, Apache, MySql, PHP) stack on the linux based server:
    https://www.codewithharry.com/blogpost/lamp-stack-ubuntu-20-04/
4: Host multiple sites from a single server:
    https://www.codewithharry.com/blogpost/host-multiple-websites-ubuntu-vps/
5: Install PHP MY ADMIN on the linux server:
    https://www.codewithharry.com/blogpost/install-phpmyadmin-ubuntu/
6: Install HTTPS Secure Certificate on the DNS registered with the server IP:
    https://www.codewithharry.com/blogpost/get-https-ubuntu-using-lets-encrypt/
7: Install LEMP (Linux, Engine-X, MySql, PHP) stack on the linux based server:
    https://www.codewithharry.com/blogpost/lemp-stack-on-ubuntu-20/
8: How to host Django Application using gunicorn & nginx in Production
    https://www.codewithharry.com/blogpost/django-deploy-nginx-gunicorn/