# Import Policies into OCM

`kubectl apply -k .`

The resources are created in their right namespaces defined in the policy object-template. 
If the resource already exists, it is updated.
If the subscription is then deleted, it doesn't delete the resource.
