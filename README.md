# Symfony 4 Docker implementation with AdminLte Bundle and FOS user bundle pre configured

This repo is something I did for my project as a combination of the following two repos
- https://github.com/tulik/symfony-4-docker-runtime-env
- https://github.com/kevinpapst/AdminLTEBundle


# Quick start

```
$ git clone https://github.com/edocabhi/symfony4-php-nginx-mariadb-docker.git
$ cd symfony4-php-nginx-mariadb-docker
$ docker-compose up
```
- Make sure to configure your environment in symfony config

Wait for containers to start, then to [http://localhost](http://localhost)

# Directory structure
```
symfony-4-docker-runtime-env
├── documentation
│   └── images
├── h2-proxy
│   └── conf.d
├── helm
│   └── symfony
│       ├── charts
│       └── templates
└── symfony
    ├── bin
    ├── config
    │   ├── packages
    │   │   ├── dev
    │   │   ├── prod
    │   │   └── test
    │   └── routes
    ├── docker
    │   ├── nginx
    │   │   └── conf.d
    │   ├── php
    │   └── varnish
    │       └── conf
    ├── public
    └── src
        ├── Controller
        ├── Entity
        ├── Migrations
        └── Repository
```

<sub><sub>
<hr noshade color="#FFFFFF" width="100%" size="1" style="padding:0; margin:8px 0 8px 0; border:none; width:100%; height: 1px; color:#FFFFFF; background-color: #FFFFFF" />

**Copyright Note:** Substantial portions of the solution was introduced by Kévin Dunglas.
</sub></sub>
