# EKSOct2026

## Materials, labs and survey
- [Labs and course materials](https://us-east-1.student.classrooms.aws.training/class/ilt%234RNEYqe9uqpKEpZZRVQ9AQ)

## Content links
- [12 factor app](https://12factor.net/)
- [A comprehensive feature comparison study of opensource container orchestration frameworks](https://arxiv.org/pdf/2002.02806)
- [CNCF's landscape of projects](https://landscape.cncf.io/)
- Kubernetes concepts
    - [Architecture](https://kubernetes.io/docs/concepts/architecture/)
    - [Pod](https://kubernetes.io/docs/concepts/workloads/pods/)
    - [Service](https://kubernetes.io/docs/concepts/services-networking/service/)
    - [Taints and tolerations](https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/)
    - [Assigning pods to nodes - affinity and anti-affinity](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#affinity-and-anti-affinity)
    - [Secret](https://kubernetes.io/docs/concepts/configuration/secret/) - **Secrets are just stored in base64 and not encrypted**
    - [Managing Secrets using kubectl](https://kubernetes.io/docs/tasks/configmap-secret/managing-secret-using-kubectl/)
    - [Job](https://kubernetes.io/docs/concepts/workloads/controllers/job/)
    - [CronJob](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
    - [Deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
    - [StatefulSet](https://kubernetes.io/es/docs/concepts/workloads/controllers/statefulset/)
    - [Kubectl rollout](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_rollout/), applyes to `StatefulSet`, `Deployment`,  `DaemonSet` 
- [AWS Secrets Manager and Config Provider for Secret Store CSI Driver](https://github.com/aws/secrets-store-csi-driver-provider-aws)
- [Get a Shell to a Running Container](https://kubernetes.io/docs/tasks/debug/debug-application/get-shell-running-container/)
- [Pod autoscaling](https://kubernetes.io/docs/concepts/workloads/autoscaling/)
- [Installing kubernetes using kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/)
- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [Admission controllers in Kubernetes](https://kubernetes.io/docs/reference/access-authn-authz/admission-controllers/)
- [eksctl](https://github.com/eksctl-io/eksctl)
- [Custom AMIs for EKS](https://docs.aws.amazon.com/eks/latest/userguide/eks-ami-build-scripts.html)
- Blueprints
    - [Bootstrapping clusters with EKS Blueprints](https://aws.amazon.com/blogs/containers/bootstrapping-clusters-with-eks-blueprints/)
    - [Terraform](https://github.com/aws-ia/terraform-aws-eks-blueprints/tree/main)
    - [CDK](https://github.com/awslabs/cdk-eks-blueprints)
- [Bottlerocket](https://github.com/bottlerocket-os/bottlerocket), open-source OS optimized for running containers
- Version upgrades
    - [Understand the Kubernetes version lifecycle on EKS](https://docs.aws.amazon.com/eks/latest/userguide/kubernetes-versions.html)
    - [Version skew policy](https://kubernetes.io/releases/version-skew-policy/)
    - [Kubernetes releases](https://kubernetes.io/releases/)