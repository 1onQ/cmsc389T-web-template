# cmsc388T-web-template
## Part 1: Hosting Website On Github Pages
### 1.1 Custom changes: 
  - **Name:** adding my name to the html file
  - **Profile Picture:** changing the profile photo to my own photo
  - **Introduction:** adding a paragraph to briefly introduce myself 
  - **Relevant Info:** adding email for reference contact 
  - **Interests:** adding a paragraph about my interest
  - **GitHub Profile:** linking my github profile to github logo
  - **LinkedIn Profile:** linking my linkedIn profile to linkedIn logo
  - **Change the style/colors:** changing the font-family; change main-header's background-color and section-header's color
### 1.2 Github Pages Site
https://1onq.github.io/cmsc389T-web-template/

## Part 2: Dockerizing WebApp
Tested docker configuration by running:
```bash
docker build -t node-web-app .
docker run --name "website" -p 80:8080 -d node-web-app 
Go to localhost:80/
```
Tested docker-compose configuration by running:
```bash
docker-compose up -d --force-recreate
Go to localhost:80/
```
Also, tested both configurations by manually running the Docker-Testing workflows

## Part 3: Deploying Website To TerpConnect

