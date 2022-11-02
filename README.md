## k8s-tutorials
This project is a complete application setup with Kubernetes components.

i deployed two applications 
- Mongodb
- Mongo-express

### kubectl commands used
    
    kubectl apply -f mongo-secret.yaml
    kubectl apply -f mongo.yaml
    kubectl apply -f mongo-configmap.yaml 
    kubectl apply -f mongo-express.yaml
