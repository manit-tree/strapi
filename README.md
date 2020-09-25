# strapi

Strapi is headless CMS that comes with REST APIs ready to use.


### Instruction

1. clone this project to your working directory
2. move to "strapi" folder. You will see docker-compose.yml + .env file
3. in your terminal, run "docker-compose pull" to download docker images (in this case strapi and mongodb)
4. then run "docker-compose up -d" to start container (in background mode)
5. when finished testing, run "docker-compose down" to remove the container

Note: if this is your first run, it might take a while for strapi to settup dependencies

If everything is OK, strapi will run on port: 1337, and Mongodb will run on port: 27017
