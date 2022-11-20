management-main
# Management Main


Based on "Fully Automated npm publish using GitHub Actions and Semantic Release" at https://www.youtube.com/watch?v=QZdY4XYbqLI

In short, we want to publish our Main service of any Management application (e.g. Automation Management), that would reside in the docker-compose file, to Node Package Manager (NPM) registry so it can be shared and imported by several Management code bases, instead of having to write and maintain this Main service in each Management repository.
