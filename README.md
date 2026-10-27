# EKSOct2026

## Materials, labs and survey
- [Labs and course materials](https://us-east-1.student.classrooms.aws.training/class/ilt%234RNEYqe9uqpKEpZZRVQ9AQ)

## Content links

### Day 1
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

### Day 2
- [kubectl api-resources](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_api-resources/)
- [Best practices for cluster upgrades](https://docs.aws.amazon.com/eks/latest/best-practices/cluster-upgrades.html)
- Some public registries
    - [AWS ECR Public gallery](https://gallery.ecr.aws/search?page=1)
    - [Docker Hub](https://hub.docker.com/search)
- [ECR Image scanning](https://docs.aws.amazon.com/AmazonECR/latest/userguide/image-scanning.html)
- [Artifact Hub](https://artifacthub.io/)
- [Helm quickstart](https://helm.sh/docs/intro/introduction)
- [Helm charts](https://helm.sh/docs/topics/charts/)
- [In-place vertical pod autoscaling](https://builder.aws.com/content/30MCh47Lw54JPCwGh0TKZgJU8d7/kubernetes-in-place-pod-resizing-vertical-scaling-without-downtime)
- [kubectl autoscale](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_autoscale/)
- [Vertical pod autoscaling](https://kubernetes.io/docs/concepts/workloads/autoscaling/vertical-pod-autoscale/) in kubernetes.io
- [repo with a vertical pod auto scaler](https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler#getting-started)
- [helm chart for the VPA](https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler/charts)
- [Cluster Autoscaler](https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler)
- [Spot placement score](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/spot-placement-score.html?refid=c938182f-f619-4856-948c-f2942a6af2ee)
- [Kubernetes Cordon: How It Works And When To Use It](https://cast.ai/blog/kubernetes-cordon-how-it-works-and-when-to-use-it/)
- [Karpenter](https://karpenter.sh/)
- Gitops
    - [What is gtops by AWS](https://aws.amazon.com/what-is/gitops/)
    - [What is gitops by RedHat](https://www.redhat.com/en/topics/devops/what-is-gitops)
    - [What is gitops by Atlassian](https://www.atlassian.com/git/tutorials/gitops)
- EKS auto-mode
    - [Getting started](https://aws.amazon.com/blogs/containers/getting-started-with-amazon-eks-auto-mode/)
    - [Autoscaling](https://docs.aws.amazon.com/eks/latest/best-practices/automode.html)
- VPC CNI
    - [repo](https://github.com/aws/amazon-vpc-cni-k8s)
    - [documentation](https://docs.aws.amazon.com/eks/latest/best-practices/vpc-cni.html)
- [Network policy in kubernetes.io ](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
- [Introducing security groups for pods](https://aws.amazon.com/blogs/containers/introducing-security-groups-for-pods/)
- [Security groups for pods](https://docs.aws.amazon.com/eks/latest/best-practices/sgpp.html)
- [Annotations for the LoadBalancer](https://docs.aws.amazon.com/eks/latest/userguide/auto-configure-nlb.html), we looked at `aws-load-balancer-nlb-target-type`, which can be `instance` or `ip`
- [Comparing different types of load balancers ](https://aws.amazon.com/compare/the-difference-between-the-difference-between-application-network-and-gateway-load-balancing/)
- [Deploying AWS Load Balancer Controller on Amazon EKS](https://aws.amazon.com/blogs/networking-and-content-delivery/deploying-aws-load-balancer-controller-on-amazon-eks/)
- [AWS Load Balancer Controller](https://kubernetes-sigs.github.io/aws-load-balancer-controller/latest/)
- [Route internet traffic with AWS Load Balancer Controller](https://docs.aws.amazon.com/eks/latest/userguide/aws-load-balancer-controller.html)