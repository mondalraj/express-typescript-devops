### Ideal Deployment Workflow:

git push → run test (eslint) → run build → build docker image → push to dockerhub → kubernetes will pull docker image → check for port and git branch → deploy and push to cloud provider (exoscale) according to branch.

Note: Manage multiple instances of environment (testing/staging/production) with external services like databases etc.

`Using Github Actions, Docker Image/Docker Hub, Kubernetes cluster (automate deployment)`
