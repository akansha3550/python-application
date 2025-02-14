# DevOps Example: Jenkins Pipeline with Docker & Minikube

* Jenkinsfile that clones the code on a build server, builds a Docker image, uploads it to DockerHub, and then deploys the application as a Pod on a separate deploy server (Minikube).
* GitHub Actions (Sonar Cloud & Snyk) run automatically on every push to the development branch, ensuring code quality and security checks.
