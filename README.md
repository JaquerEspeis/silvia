# Deploy Cluster
Add token to env

```
source env
```

```
terraform apply
```

# Install and configure sonarqube
```
helm -n sonarqube install tools-sonarqube ./ --create-namespace --wait
```
