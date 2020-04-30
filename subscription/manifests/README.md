# Import Manifests into OCM

`kubectl apply -k .`

If the resources already exist, subscription backs off and the resource is not updated. 
Message: `Obj /cluster exists and owned by others, backoff`
The resource is created in the namespace of the subscription. eg open-cluster-management.
If the subscription is deleted, the resource is deleted too.
