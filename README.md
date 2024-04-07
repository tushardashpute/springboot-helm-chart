# springboot-helm-chart

To install Helm chart:

helm  --install springboot springboot/ --set serviceAccount=true

To upgrade helm chart:

helm upgrade  --install springboot springboot/ --set serviceAccount=true

Your app will be running on port 33333.
