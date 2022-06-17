### INSTALL COMPOSER DEPENDENCY

- Run `composer install` to install the project dependencies

### RUN DOCKER

- Make sure that Docker desktop or Docker services are running and run `docker compose up`
- After the docker image has finished and is running, go to "http://localhost:8080". If is the first time running the project, WordPress will start the installation project
- To access the backend go to "http://localhost:8080/wp/wp-admin/"

PLEASE NOTE: Bedrock adds a "/wp" slug to the URL for the backend

### RUN THEME FOR DEVELOPMENT

- Go to the folder "/web/app/themes/linkem-blog" and run `composer install` if it's the first time running the theme
- Run `yarn` or `npm i` to install dependencies
- Run `yarn dev` or `npm run dev` to start the theme in dev mode

### BUILD THE THEME FOR PRODUCTION

- For production the theme should always run `composer install` (in case new dependencies are added)
- Run `yarn` or `npm i` to install dependencies
- Run `yarn build` or `npm run build` to build the theme
- The theme folder can now be used/placed in the theme folder
