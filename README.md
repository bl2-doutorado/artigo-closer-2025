# CLOUD 2025 - Towards an automated choice of topology for cloud application deployment based on FinOps practices

This repository contains files automatically generated by G-FinOps tool presented in the paper "Towards an automated choice of topology for cloud application deployment based on FinOps practices" submitted to CLOUD 2025. The files were generated to the following applications:

- Wonky (https://github.com/domix/wonky)
- Jeeshop (https://github.com/RealJeeshop/jeeshop)
- Homepage (https://github.com/gethomepage/homepage)

[dockerfiles](./dockerfiles/) directory contains Dockerfiles generated by G-FinOps to the same applications. Each application has its own subdirectory.

[charts](./charts/) directory contains Helm charts generated by G-FinOps, that enable the deploy of these applications to a Kubernetes cluster. Each chart is inside a subdirectory with the name of the application.
