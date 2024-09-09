# ISEC6000-SecureDevOps
*Manage and version project files, code, and configurations for ISEC6000-SecureDevOps*

> This assignment has explored deploying a multi-containerized web service to a Kubernetes cluster.

---

### This has been achieved through the following steps:
1. Create a Kubernetes cluster
2. Install and configure `kubectl` and `gcloud` within the local environment
3. Setup a GitHub account and repositories
4. Install and configure `kompose` within the local environment
5. Fork Saleor GitHub repository to the local environment
6. Customize and convert `docker-compose` with Kompose, in preparation for deployment
7. Deploy the Saleor Platform to a Kubernetes cluster

---

Further to this, security adaptations were made to improve the container security. The cluster was setup with `trivy-operation` to undertake continuous monitoring of vulnerabilities.

*This includes*
- Changing to non-root user.
- Setting resource limits.
- Ensure secure base images.

All changes were merged with the forked repository by using `git`.

---

Finally, a graphical representation of the system's architecture has been developed to demonstrate the components that have been launched to the cluster and their interactions.

---

Details of all the above can be found in the **submitted project documentation PDF**.

| Section |             Heading            |
|---------|--------------------------------|
| 1       | Setup intial infrastructure    |
| 2       | Create microservice and deploy |
| 3       | Implementing security measures |
| 4       | Architecture visualisation     |

