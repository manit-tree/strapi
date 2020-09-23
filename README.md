# strapi

Strapi is headless CMS that comes with REST APIs ready to use.

to run strapi container on you development machine, pls follow these steps.

1. clone this repository to your working directory
2. move inside your working directory. You will see docker-compose.yml + .env file
3. in your terminal, run "docker-compose pull" to download docker images (in this case strapi and mongodb)
4. then run "docker-compose up -d" to start container in the background mode

Note: if this is your first run, it might need to wait a while for strapi to settup dependencies

If everything is OK, strapi container will run on port: 1337, and Mongodb container will run on port: 27017
