# QuakeKube

A helm chart for QuakeKube is a Kubernetes-ified version of QuakeJS that runs a dedicated Quake 3 server in a Kubernetes Deployment, and then allow clients to connect via QuakeJS in the browser.

Install

```
# Add the repo
helm repo add grahamplata https://grahamplata.github.io/chart

# Install
helm install --set quakeServer.eula=true grahamplata/quake-kube
```

> Source https://github.com/criticalstack/quake-kube
