apiVersion: apps/v1
kind: Deployment
metadata:
  annotations:
    oncallPager: 800-555-1212
  name: example
spec:
  template:
    metadata:
      annotations:
        oncallPager: 800-555-1212
