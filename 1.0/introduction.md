# Introduction

[[toc]]

## What is Forge?

Laravel Forge is a server management and site deployment service. After connecting to your preferred server provider, Forge will provision a new server, installing and configuring:

- Nginx
- PHP
- MySQL / Postgres / MariaDB (if selected)
- Logrotate
- Firewalls
- Opcache
- Memcached
- Redis

After a server has provisioned, you can then deploy your custom websites or Wordpress through the Forge panel.

Forge does not currently provide:

- Server support
- Database or file backups

## Learning More

Laracasts has a comprehensive and **free** [video course](https://laracasts.com/series/learn-laravel-forge) on Forge which you should check out if you're using Forge for the first time.

## Forge IP Addresses

If you are restricting SSH access to your server using IP whitelisting, you should whitelist the following IP addresses:

- `159.203.161.246`
- `159.203.163.240`

:::tip IP Address Changes

The Forge IP addresses may change from time to time; however, we will always email you several weeks prior to an IP address change.

:::