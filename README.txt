Test:

Create Applicationset in ACM
Protect the resource in the cluster with argocd.argoproj.io/sync-options: Delete=false
Delete the ApplicationSet
Check that the resouce is still there

Next:
Create a Policy from the resource
Set Policy to inform and check that Policy is compliant
