# Multiple ingress controllers - 1 cluster

This is an example of how to run 2 nginx ingress controllers on a k8s cluster on AWS.

By adding the annotation `ingress.kubernetes.io/ingress.class: nginx-gateway` to the second ingress yaml, that ingress will apply to the second ingress controller.

![diagram](https://user-images.githubusercontent.com/10458699/34580087-8197b462-f140-11e7-914d-5439a48e44f1.png)

