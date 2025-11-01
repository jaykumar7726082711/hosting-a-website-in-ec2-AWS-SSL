# hosting-a-website-in-ec2-AWS-SSL
## step to deploy
1. launch EC2 instance
1. go to aws console ,then EC2 then lonch instance 
2. choose ubuntu
3. creat and use key pair 
4.use putty 
5. ALLOW HTTP(80), HTTPS(443) and SSH(2)
6. lounch instance

## 2. Connect to EC2 (using PuTTY/SSH)
* Download Putty.exe file and install it in your device.
* Go to connection.
*Go to SSH
* Go to Auth
* Choose key pair file you made while creating instance.

* login as username: ubuntu
3. Install Apache
* sudo apt install apache2
Check in browser → http://yourpublicip

### An Apache page will be shown to your public ip.
* cd /var/www/html
* sudo rm index.html
* sudo vi index.html
* Press I to insert your own html code.
### Write your own code.
* After writing all code , Press Ctrl+C and then write ":wq" and Press Enter.

