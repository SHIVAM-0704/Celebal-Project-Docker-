---
page_type: sample
languages:
- yaml
products:
- azure
description: "Multi-container using Docker Compose in Azure Web App for Containers."
urlFragment: docker-compose-web-app-sample
---

# Multi-container using Docker Compose in Azure Web App for Containers
This custom image is based on the 'official image' of [WordPress from Docker Hub](https://hub.docker.com/_/wordpress/).

The following changes have been made in this custom image:
* [Explicitly uses WordPress 4.9.5, PHP 7.2 and Apache.]()
* [Adds PHP extension for Redis v4.0.2.]()
* [Adds Baltimore Cyber Trust Root Certificate file for SSL to MySQL.]()
* [Uses App Setting for MySQL SSL Certificate Authority certificate in WordPress wp-config.php.]()
* [Uses App Setting for Redis host name in WordPress wp-config.php.]()
* [Uses Redis Object Cache 1.3.8 WordPress plugin.]()


