
    kubectl create ns oasis
    kubectl config set-context --current --namespace=oasis

    kubectl apply -f minecraft.yaml
    kubectl get pods
    kubectl logs ...
    kubectl exec -it ... bash
    # If it doesn't even start, then first uncomment sleep command in YAML.

    kubectl delete -f minecraft.yaml
