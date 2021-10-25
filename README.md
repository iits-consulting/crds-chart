## Usage

These are custom resource definitions for commonly used iits helm charts. This crds should be rolled out upfront so that
all the other helm charts, which need theses crds, can work without issues.

How to install:

```shell
    export CHART_NAME=crds
    export CHART_REPO_NAME=crds-chart
    helm repo add $CHART_REPO_NAME https://iits-consulting.github.io/$CHART_REPO_NAME/
    helm search repo $CHART_NAME
    helm install $CHART_NAME $CHART_REPO_NAME/$CHART_NAME
```