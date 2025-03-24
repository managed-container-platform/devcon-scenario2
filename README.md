# devcon-scenario2

This scenario2 have a helm char application, where you need to install this application in your cluster.

## Pre-requisites

- You should have kubectl and helm binaries installed.
- You should deploy this application in `scenario2` namespaces only

## Deploying application using helm

To deploy this application using helm, clone this repo locally and can use the below command.

```bash
helm upgrade -i --create-namespace -n scenario2 demoapp-2 . -f values.yaml
```

## Troubleshoot the error

There is an issue with the manifest ,fix the error and deploy the application using above command.