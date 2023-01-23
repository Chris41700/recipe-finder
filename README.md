# Quickcook
A Dockerize PHP React application using [themealdb.com](https://www.themealdb.com/api.php) API and Material UI for frontend. The goal of this website is to help people learn new culinary recipes quickly and easily. When you search for a recipe, it will provide the name, image, recipe, ingredients and measurements, YouTube video, and source website.

## How to install & run
- Install [PHPStorm](https://www.jetbrains.com/phpstorm/) and [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- Clone the repository from Github into PHPStorm
- In the Dockerize-PHP-Application path, run ``` docker build -t mydemophpimage . ```
- In the frontend/react-docker path, run ``` docker build -t mydemoreactimage . ```
- Run ``` docker-compose up ```

## Project Running
https://user-images.githubusercontent.com/60550186/211950978-f25f564b-60e1-4645-a131-ef63d47ec7f7.mp4

## Next Steps
- [ ] Deploy full stack application onto AWS
