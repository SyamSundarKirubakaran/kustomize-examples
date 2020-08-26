output:
```
apiVersion: apps/v1
kind: Deployment
metadata:
  name: the-deployment
spec:
  replicas: 3
  template:
    containers:
    - image: registry/the-container:latest
      name: the-container
```
