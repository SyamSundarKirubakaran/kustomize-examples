Output:
```
apiVersion: apps/v1
kind: Deployment
metadata:
  name: the-deployment
spec:
  replicas: 5
  template:
    containers:
    - image: registry/conatiner:1.0.0
      name: the-container
```
