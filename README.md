# Example Voting App - Kubernetes Deployment

These are the kubernetes configuration files for the [example-voting-app](https://github.com/dockersamples/example-voting-app) project from the [docker-samples](https://github.com/dockersamples) github page.

## Usage

### Clone Repository

```
git clone https://github.com/durrezahmed/example-voting-app-kubernetes.git
```

```
cd example-voting-app-kubernetes
```

### Run the following command to create the deployments and services objects:

```
kubectl create -f .
```

The vote interface is then available on port 30004 on each host of the cluster, the result one is available on port 30005.
