# Docker setup for demoing integrations

1. Clone this repository
2. Install [Docker](https://www.docker.com/get-docker)
3. In a terminal window, navigate to the directory where you cloned the repo
4. Run:
    ```docker
    docker build -t android_jenkins .
    docker run -p 4000:8080 android_jenkins
    ```
5. Make sure you grab the admin password from the logging output
6. Go to `localhost:4000` and complete the setup steps.

Some configuration will need to be done to set up a security policy and the app project itself. But the container should be able to spin up ready to go.