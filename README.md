# wordpress-docker-development-environment

A simplified yet refined Docker Compose workflow of containers for local WordPress development.
## 🏠 WP Environment

WordPress always gets the latest version.

- WP ver latest
- PHP ver 8.0
- WP-CLI
- Mariadb ver 10.5.8
- Phpmyadmin

## 🐶 Usage Environment

- [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
- Node.js >= 16

## 😌 Usage
To get started, make sure you have Docker installed on your system, and then clone this [repository](https://github.com/YevheniiVolosiuk/wordpress-docker-development-environment.git).
1. Copy and past `.env.exeplmle` to your **_ROOT_** directory and change name for new file to `.env`.
2. Next, navigate in your terminal to the directory you cloned this, and spin up the containers for the web server by running.

```bash
docker-compose up -d
```
After that completes, get your WordPress installation in to `/wordpress` folder.

Next you can open your WordPress site
- wp frontend

open in browser <http://localhost/>

- wp admin

open in browser <http://localhost/wp-admin/>

Credentials:
```bash
user : admin
password : password
```

Also, you can open your **_phpmyadmin_** db visualiser
- phpmyadmin

open in browser <http://localhost:8081/>

## 👀 Document

- [docker](https://docs.docker.com/)
- [docker-wordpress-image](https://hub.docker.com/_/wordpress)
