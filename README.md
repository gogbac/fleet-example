# fleet-example - UNDER CONSTRUCTION

#This simple fleet-example is to show how to deploy an app via fleet functionality in Rancher 2.6 to multiple kurbenetes clusters

#These are the manual steps to test the 3 Apps:

AQUARIUM App
============

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

FIREPIT App
===========

Step 1
- create a "firepit.yaml"

Step 2
- kubectl create -f firepit.yaml

Step 3
- kubectl get pods -w

Step 4
- kubectl logs -f firepit
- this should display an firepit
- Ctrl + C to exit
- 'clear' the screen

Step 5 
- kubectl delete pod firepit

FUNBOX App
===========

Step 1
- create a "funbox.yaml"

Step 2
- kubectl create -f funbox.yaml

Step 3
- kubectl get pods -w

Step 4
- kubectl logs -f funbox
- this should display an funbox
- Ctrl + C to exit
- 'clear' the screen

Step 5 
- kubectl delete pod funbox

