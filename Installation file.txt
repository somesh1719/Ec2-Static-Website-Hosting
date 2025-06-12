# Ec2-Static-Website-Hosting
1 sudo su
2 yum update -y
3 yum install httpd -y
4 cd /var/www/html/
5 vim index.html
6 cat index.html
7 service httpd start
------------------------------->>
step to hosting satic html website hosting by using ec2 and httpd web server---->>

step 1:- Login Aws account and in dashboard search ec2 instance
step 2:- Create Ec2 instance selece amazone aws ami machine image and select instace type t2 micro 
because this type of instance is free and its give 8gb storage to deploy any web image and server
now allow all acl create one network group assign 000.00 port because we host website public server
now selet on key pair there are two type of key 1st is .pem and 2nd is .ppk for putty now we create instance
step 3:- connect instance with ssh secure shell now we click on command promt write 1st command 
is cd dawnloads 
because key store in downloads folder thats why we select dawnloads cd for change directory
step 4:- go to ec3 instance click on connect and now copy ec2 ssh command given in down 
side now past this command on cmd
step 5:- now instance succesfully connect with ssh now we write sudo su for switch user to root user 
now we add yum update -y command for updation 
step 6:- other step we install httpd server to run html wesite add yu install httpd -y and another 
step we go to var/www/html use cd cammand in this directory we create onefile bye using vim index.html in this command 
open vim editor simply we add code in this vim file now we use service httpd start command for star httpd server
step 7: now we go to ec2 instance and copy private ip and paste on browser out display on browser

 

