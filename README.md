Continuous Delivery:   Automates testing and staging; requires manual approval for production.
Continuous Deployment:  Fully automates the entire release process, deploying to production automatically after passing tests.
-----------------------------------------------------------------------------------------------------------------------------------
PLUGINS USED TI CONNECTED IN JENKINS BY OTHER TOLLS

Git Plugin:              To pull the source code from a Git repository.
Maven Integration Plugin: To build the project.
JUnit Plugin:             To run unit tests and publish results.
SonarQube Scanner:        To analyze code quality.
Docker Plugin:            To build a Docker image of the application.
Nexus Artifact Uploader: To upload the Docker image or JAR files to Nexus.
Email Extension Plugin: To notify team members of build results.
Kubernetes Plugin:     For deploying applications to a Kubernetes cluster.
Prometheus Plugin:     For monitoring Jenkins with Prometheus.
Deploy to Container Plugin:  For deploying to application servers like Tomcat.
