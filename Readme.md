###Epho Embedded Notice

#nginx reverse proxy test

This config is use for test nginx reverse proxy.

Test env: nginx, node.js-pm2, ip, domain, dns, certbot.

---
#experiment:
- Configurate your ip:1.2.3.4 dns-> sample.com.
- Deploy your node.js backend and startup in pm2.
- Install nginx and configurate the server block (without ssl).
- Install certbot for certification(https) when checkout shell-cmd "nginx -t" successed and test ok in reverse proxy pass to node.
- Configure the nginx conf server block such as the template "test_ssl", then you can reverse proxy in https with ssl.
---
