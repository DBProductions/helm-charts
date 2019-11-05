# Helm Charts

Public Helm chart repository as an example served with Githug pages.

    helm lint charts/*
    helm package charts/*
    helm repo index --url https://github.com/DBProductions/helm-charts/ .
    helm repo index --url https://github.com/DBProductions/helm-charts/ --merge index.yaml .

    helm repo add myhelmrepo https://dbproductions.github.io/helm-charts/