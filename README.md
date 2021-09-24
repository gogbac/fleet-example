# fleet-example

#This fleet-example is to show how to deploy apps via fleet functionality in Rancher 2.6

Step 1
- create a "aquarium.yaml"

Step 2
- kubectl create -f aquarium.yaml

Step 3
- kubectl get pods -w

Step 4
- kubectl logs -f aquarium

- this should display an aquarium
