# TF-controller Helm Chart

## Installation

Before using TF-controller, you have to install Flux by using either `flux install` or `flux bootstrap` command.

1. Add TF-controller repository to Helm repos

    ```bash
    helm repo add tf-controller https://tf-controller.github.io/charts/
    ```

2. Install TF-controller

    ```bash
    helm upgrade -i tf-controller tf-controller/tf-controller \
    --namespace flux-system
    ```

For more details on installing TF-controller, please see the [chart readme](./charts/tf-controller/README.md). 