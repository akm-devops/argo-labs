kustomize build --enable-helm ./argo-cd | kubectl apply -f -

kustomize build --enable-helm ./argo-cd | kubectl delete -f -
