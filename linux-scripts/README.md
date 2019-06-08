## Introduction 
I am leaving this file here so that you can remember how to admin some of the stuff on this server. 

## DNS - Bind9
### Introduction 
I am using bind9 to admin the local dns. 

### Start and restart
sudo /etc/init.d/bind9 restart
sudo /etc/init.d/bind9 stop 

Testing 
sudo vim  /etc/resolv.conf

## Mail server
### Introduction 
I am using postfix for sending mails from this server. It is running as a service therefore see scripts below.
### Usefull scripts 
sudo /etc/init.d/postfix status

