sample secure copy command: 

 scp -P 2222 .\id_rsa* vagrant@localhost:
 scp -P <scp port number> <source file to copy> <username>@<server ip/fqdn>

fqdn is the fully qualified domain name
this is a sample command for copying over ssh files
vagrant in the sample command is the user 
-P 2222 is to change the port from 22 (which is the default)
localhost can be replaced by an IP address
to securely copy file 
