## test mudole
- [x] list1
- [ ] list2

# Let's encrypt
### https://certbot.eff.org/#ubuntuxenial-nginx
  ```
$ sudo add-apt-repository ppa:certbot/certbot
$ sudo apt-get update
$ sudo apt-get install certbot 
$ certbot certonly -d slash.tw -d www.slash.tw
  ```
### Automating renewal
```
$ certbot renew --dry-run
```
### or use https://www.linode.com/docs/security/ssl/install-lets-encrypt-to-create-ssl-certificates

# Docker
### https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
