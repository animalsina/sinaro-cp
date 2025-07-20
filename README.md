
# [WP] ROCP - Ragnarok Online Control Panel

![Laravel](https://img.shields.io/badge/Laravel-12-red)
![Livewire](https://img.shields.io/badge/Livewire-v3-orange)
![PHP](https://img.shields.io/badge/PHP-8.4-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-green)
![MySQL](https://img.shields.io/badge/MySQL-lightgrey)
![License: SinaRO CP](https://img.shields.io/badge/license-SinaRO_CP_v1.2-blue)



### ⚙️ Used Tecnologies

- PHP 8.4
- Laravel 12
- Livewire 3
- Tailwind CSS
- MongoDB
- MySQL
- Docker
- FrankenPHP (opzionale)

---

**ROCP** is a modern control panel for *Ragnarok Online* servers based on **rAthena**, built using **Laravel 12**, **Livewire 3**, and **PHP 8.4**.

It’s designed to be flexible and performant, with optional support for **FrankenPHP** to greatly improve deployment and performance. However, ROCP also works perfectly on traditional stacks with **Nginx + PHP-FPM**.

It uses both **MySQL** and **MongoDB** as data sources and includes a complete Docker setup to run the entire server and connect all components with a single file.

### ✨ Key Features

- Full account and character management
- Deep rAthena integration
- Dynamic interface powered by Livewire 3
- Compatible with PHP 8.4, MySQL, MongoDB
- One-command full server setup via Docker
- FrankenPHP support (optional, not required)
  
## 📜 Credits

ROCP was built using a range of powerful open source tools and technologies:

- [Laravel](https://laravel.com) – PHP framework for building modern web applications  
- [Livewire](https://livewire.laravel.com) – Full-stack framework for dynamic UIs in Laravel  
- [Tailwind CSS](https://tailwindcss.com) – Utility-first CSS framework for styling  
- [FrankenPHP](https://frankenphp.dev) – Modern PHP application server for high-performance Laravel deployments  
- [PHP](https://www.php.net) – Core backend programming language  
- [MySQL](https://www.mysql.com) – Relational database used for account and character data  
- [MongoDB](https://www.mongodb.com) – Document database for additional or extended datasets  
- [Docker](https://www.docker.com) – Containerization platform used to simplify deployment and environment consistency
---

## 🙏 Acknowledgements

Special thanks to the open source community and to the teams behind the tools that make this project possible:

- The Laravel core team, for providing an elegant and modern PHP framework  
- The Livewire team, for simplifying reactive interfaces in Laravel  
- The Tailwind CSS team, for their utility-first CSS philosophy and beautiful defaults  
- Kevin Dunglas and contributors of FrankenPHP, for building a next-gen PHP application server  
- The PHP community, for decades of evolution and open collaboration  
- The developers behind MySQL and MongoDB, for robust, reliable data storage solutions  
- The Docker team and community, for enabling seamless development, testing, and deployment  

**SinaRO CP** wouldn’t exist without these powerful foundations.  
Thank you all.

*– AnimaL Sina – Creator of SinaRO CP*

## 🐳 Docker Setup

```bash
git clone https://github.com/animalsina/sinaro-cp.git
cd sinaro-cp
cp .env.example .env
docker compose up -d
```

The container includes everything: web server, PHP, databases and ready-to-use config.

---

## Demo of the CP
[SinaRO CP](https://rocp.animalsina.work)

---

## 🪪 License

This project is proprietary.  
You are allowed to use and modify it for **personal or private use only**.

Any commercial use, redistribution, or resale is **strictly forbidden** without written permission.  
See [LICENSE](LICENSE) for full terms.
