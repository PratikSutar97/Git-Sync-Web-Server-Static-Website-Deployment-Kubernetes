# Git-Sync-Web-Server-Static-Website-Deployment-Kubernetes
A company wants its static documentation website to update automatically from GitHub. Containers: Container 1: Nginx (serves static files) Container 2: Git-sync sidecar (clones/pulls repo periodically) Flow: Git-sync pulls latest files into a shared volume. Nginx serves those files.
