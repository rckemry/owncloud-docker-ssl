More info coming soon! This is a work in progress..

Steps:
I set this up on a windows machine using WSL with Ubuntu 20.04.5 LTS
Windows: https://docs.docker.com/docker-for-windows/install/
macOS: https://docs.docker.com/docker-for-mac/install/
Linux: Install the Docker Engine and Docker Compose according to your OS specifics

1. Open your Ubuntu CLI
2. mkdir owncloud-docker-nginx
3. vi .env
    -Add the contents of ithe .env file above, fill in your parameters and save.
4. vi docker-compose.yml
    -Add the contents of the docker compose file above, no changes needed and save.
5. docker-compose up -d
    -Once the containers are provisioned navigate to localhost:8080 and log in with the admin credentials specified in .env
6. PROFIT!!

Tips:
Set up port forwarding on your router for 8080, 80, and 443.
Ensure your firewall is not block these ports as well.
I simply registerd my somin using my routers dynamic DNS feature.