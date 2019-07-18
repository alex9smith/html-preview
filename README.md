# HTML Preview

Runs nginx in a Docker container to serve local HTML files while working on them. Currently includes a very basic [Materialize](https://materializecss.com/getting-started.html) template and a separate CSS file.

## How to use
1. Clone or download this repository
2. Install [Docker](https://docs.docker.com/install/)
3. Navigate to the repository folder in a command line shell
4. Type `docker-compose up`
5. Go to [localhost:8080](http://localhost:8080) in your browser
6. Make changes to the HTML and CSS files in `/html` and reload the browser to see them
7. When you've finished, go back to your command line and press `Ctrl+C` then type `docker-compose down` to stop the container.