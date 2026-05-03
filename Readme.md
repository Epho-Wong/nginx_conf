###Epho Embedded Notice

#nginx reverse proxy test

This config is use for test nginx reverse proxy.

Test env: nginx, node.js-pm2, ip, domain, dns, certbot.

experiment:
1.Configurate your ip:1.2.3.4 dns-> sample.com.
2.Deploy your node.js backend and startup in pm2.
3.Install nginx and configurate the server block (without ssl).
4.Install certbot for certification(https) when checkout shell-cmd "nginx -t" successed and test ok in reverse proxy pass to node.
5.Configure the nginx conf server block such as the template "test_ssl", then you can reverse proxy in https with ssl.
