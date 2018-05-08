# Docker setup for demoing integrations

1. Clone this repository
2. Install [Docker](https://www.docker.com/get-docker)
3. In a terminal window, navigate to the directory where you cloned the repo
4. Run:
``` docker build -t android_jenkins .
docker run -p 4000:8080 android_jenkins

5. Make sure you grab the admin password from the logging output
6. Go to `localhost:4000` and complete the setup steps.

