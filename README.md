# Hi, I'm Gopala

I'm a DevOps engineer in Bloomington, Illinois. I build the pipelines, Kubernetes clusters and GPU platforms that get software and machine learning models in front of real users.

I like boring releases: small changes, automated checks, and a rollback that takes minutes.

## What I work with

- **Cloud:** AWS, GCP, Azure
- **Infrastructure as code:** Terraform, CloudFormation
- **Delivery:** GitHub Actions, Jenkins, ArgoCD
- **Containers:** Docker, Kubernetes, Helm
- **Watching it run:** Prometheus, Grafana, ELK
- **Security:** Vault, Trivy, Snyk
- **Languages:** Python, Bash

## Worth a look

- **[My portfolio](https://github.com/gkakkineni-devops/gkakkineni-devops.github.io)** is plain HTML, CSS and JavaScript, but I run it like a real service. Every push goes through lint, HTML and link checks, a Trivy scan and a container smoke test before it deploys. A health check runs every three hours, and the panel on the home page shows the live results. It costs $0.
- **[observability-stack](https://github.com/gkakkineni-devops/observability-stack)** is a small Prometheus, Alertmanager and Grafana setup that starts with one command. The alert rules have unit tests, and CI starts the whole stack and checks that a real alert fires.
- **[gitops-canary-rollouts](https://github.com/gkakkineni-devops/gitops-canary-rollouts)** is a Helm chart that releases a service as a canary with Argo Rollouts, synced by Argo CD. CI runs a good release and a bad one on a real kind cluster, and checks that the bad one gets stopped.
- **[terraform-aws-eks-gpu](https://github.com/gkakkineni-devops/terraform-aws-eks-gpu)** is Terraform for an EKS cluster with a GPU node group that sits at zero until you need it. It's validated and scanned in CI, but I haven't applied it to a real account.

## Find me

- Portfolio: [gkakkineni-devops.github.io](https://gkakkineni-devops.github.io/)
- LinkedIn: [gopala-krishna-devops](https://www.linkedin.com/in/gopala-krishna-devops)
- Email: gopalakrishnaakkineni.dev@gmail.com

I'm looking for DevOps, SRE and platform engineering roles.
