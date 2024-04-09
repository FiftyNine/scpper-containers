# scpper-containers
A meta-repo for quick deployment of all scpper components using Docker containters.

## Instructions
 - Make local copies of all scpper components in the same parent folder  
`git clone https://github.com/FiftyNine/scpper-db`  
`git clone https://github.com/FiftyNine/scpper-web`  
`git clone https://github.com/FiftyNine/scpper-crawler`
 - Copy `docker-compose.yml` and `.env` files into that parent folder.
 - Run `docker compose up --build --force-recreate`
