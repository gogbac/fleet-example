# fleet-example

#This simple fleet-example is to show how to deploy an app via fleet functionality in Rancher 2.6 to multiple kurbenetes clusters

Step 1
- create a "aquarium.yaml"

Step 2
- kubectl create -f aquarium.yaml

Step 3
- kubectl get pods -w

Step 4
- kubectl logs -f aquarium
- this should display an aquarium
- Ctrl + C to exit
- 'clear' the screen

Step 5 
- kubectl delete pod aquarium
