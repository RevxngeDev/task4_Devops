# task4_Devops


## Overview
Launches an Nginx web server and a MySQL database on a custom bridge network (`10.10.10.0/28`), with data persistence and DNS aliases.

## Files
- **docker-compose.yml**  
- **nginx/default.conf**  

## Steps

1. **Start the stack**  
   ```bash
   docker compose up -d
