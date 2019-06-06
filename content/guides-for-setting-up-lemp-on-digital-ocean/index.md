---
title: "Guides for Setting up LEMP on Digital Ocean"
description: "This will install PHP 7.0, if you want to install PHP ≥ 7.1 follow the note after this link (when you’re about to install PHP stop and read that note). In case you need PHP 7.1 instead of PHP 7.0…"
date: "2017-07-03T19:08:38.227Z"
categories: 
  - Linux
  - PHP
  - MySQL
  - Cloud

published: true
canonical_link: https://medium.com/@AAlakkad/guides-for-setting-up-lemp-on-digital-ocean-30d91b0dd896
redirect_from:
  - /guides-for-setting-up-lemp-on-digital-ocean-30d91b0dd896
---

![](./asset-1.png)

I’ll be very direct, follow the following guides (most of them are from digital ocean):

### Initial Server Setup

Create a new droplet with Ubuntu 16.04, then go through:

[**Initial Server Setup with Ubuntu 16.04 | DigitalOcean**  
_When you start a new server, there are a few steps that you should take every time to add some basic security and give…_www.digitalocean.com](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04 "https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04")[](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04)

### Install the LEMP (Linux, Nginx , MySQL, PHP) stack

This will install PHP 7.0, if you want to install PHP ≥ 7.1 follow the note after this link (when you’re about to install PHP stop and read that note).

[**How To Install Linux, Nginx, MySQL, PHP (LEMP stack) in Ubuntu 16.04 | DigitalOcean**  
_The LEMP software stack is a group of software that can be used to serve dynamic web pages and web applications. This…_www.digitalocean.com](https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-in-ubuntu-16-04 "https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-in-ubuntu-16-04")[](https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-in-ubuntu-16-04)

#### Note:

In case you need PHP 7.1 instead of PHP 7.0, follow this guide when you reach the step for installing PHP:

[**Vultr: High Performance SSD Cloud.**  
_Deploy high performance SSD VPS on the worldwide Vultr network in 60 seconds. Sign up for free and start hosting…_www.vultr.com](https://www.vultr.com/docs/how-to-install-and-configure-php-70-or-php-71-on-ubuntu-16-04 "https://www.vultr.com/docs/how-to-install-and-configure-php-70-or-php-71-on-ubuntu-16-04")[](https://www.vultr.com/docs/how-to-install-and-configure-php-70-or-php-71-on-ubuntu-16-04)

### Create MySQL database and user

After setting up the LEMP stack, create a database and a user for your application(s), please don’t use the `root` account, never.

[**How To Create a New User and Grant Permissions in MySQL | DigitalOcean**  
_The lines that the user needs to enter or customize will be in red in this tutorial! The rest should mostly be copy-and…_www.digitalocean.com](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql "https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql")[](https://www.digitalocean.com/community/tutorials/how-to-create-a-new-user-and-grant-permissions-in-mysql)

### Install SSL certificate

[**How To Secure Nginx with Let's Encrypt on Ubuntu 16.04 | DigitalOcean**  
_In this tutorial, we will show you how to use Let's Encrypt to obtain a free SSL certificate and use it with Nginx on…_www.digitalocean.com](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04 "https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04")[](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-16-04)

---

You can [sign up on Digital Ocean](https://m.do.co/c/871e80a46953) and get 10$ for free using my referral link.

For me I always come back to Digital Ocean guides regarding the servers, what about you?
