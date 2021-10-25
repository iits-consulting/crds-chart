## Usage

These are custom resource definitions

How to install:

```shell
    export CHART_NAME=crds
    export CHART_REPO_NAME=crds-chart
    helm repo add $CHART_REPO_NAME https://iits-consulting.github.io/$CHART_REPO_NAME/
    helm search repo $CHART_NAME
    helm install $CHART_NAME $CHART_REPO_NAME/$CHART_NAME
```