This is code to create a deployment with one replica of your Discord bot and expose it through a LoadBalancer service.

These are the commands to run it. 
kubectl apply -f discord-bot-deployment.yaml
kubectl apply -f discord-bot-service.yaml

