# Hi, I'm Gopala

I'm a DevOps engineer in Bloomington, Illinois. I build the pipelines, Kubernetes clusters and GPU platforms that get software and machine learning models in front of real users.

I like boring releases: small changes, automated checks, and a rollback that's one revert away.

## What I work with

- **Cloud:** AWS, GCP, Azure
- **Infrastructure as code:** Terraform, CloudFormation, tflint
- **Delivery:** GitHub Actions, Jenkins, Buildkite, ArgoCD, FluxCD, Argo Rollouts
- **Containers:** Docker, Kubernetes, Helm, kind
- **Watching it run:** Prometheus, Alertmanager, Grafana, ELK
- **Security:** Vault, Trivy, hadolint, Snyk, SonarQube
- **Scripting:** Python, Bash, Linux, Nginx

## Worth a look

- **[My portfolio](https://github.com/gkakkineni-devops/gkakkineni-devops.github.io)** is plain HTML, CSS and JavaScript, but I run it like a real service. Every push goes through lint, HTML and link checks, a Trivy scan and a container smoke test before it deploys. A health check runs every three hours, and the panel on the home page shows the live results. It costs $0.
- **[observability-stack](https://github.com/gkakkineni-devops/observability-stack)** is a small Prometheus, Alertmanager and Grafana setup that starts with one command. The alert rules have unit tests, and CI starts the whole stack and checks that a real alert fires.
- **[gitops-canary-rollouts](https://github.com/gkakkineni-devops/gitops-canary-rollouts)** is a Helm chart that releases a service as a canary with Argo Rollouts, synced by Argo CD. CI runs a good release and a bad one on a real kind cluster, and checks that the bad one gets stopped.
- **[terraform-aws-eks-gpu](https://github.com/gkakkineni-devops/terraform-aws-eks-gpu)** is Terraform for an EKS cluster with a tainted GPU node group on Spot that sits at zero until you need it. API access is limited to listed IPs. CI runs validate, tflint and a Trivy scan, but I haven't applied it to a real account.

## Find me

- Portfolio: [gkakkineni.dev](https://gkakkineni.dev/)
- LinkedIn: [gopala-krishna-devops](https://www.linkedin.com/in/gopala-krishna-devops)
- Email: gkakkineni.dev@gmail.com

I'm looking for DevOps, SRE and platform engineering roles.
