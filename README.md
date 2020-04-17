# Olivier Boukili

*Cloud engineer with a strong sysadmin background and a passion for DevSecOps culture.*

---

### Technical Skills


**Cloud Providers**
* Google Cloud (experimented)
* AWS

**Services**
* Kubernetes
* Linkerd 2 Service Mesh
* Vault
* ArgoCD
* Consul
* Traefik
* Prometheus
* Sensu
* Gloo API Gateway
* Kong API gateway
* Jaeger Opentracing

**Languages**
* Go
* Python

**Tools:**
* GoLand IDE
* Terraform
* Kustomize
* Gitlab
* Ansible

---

### Experience

* *2020-present* **Keplr / Principal Cloud Engineer**
   * **Milestones**:
     * Designed and implemented a 'scale to 0', fast, and highly concurrent CI with GitlabCI using GKE preemptible nodes for the whole company's projects (Golang / NodeJS).
     * Introduced and migrated the legacy reverse proxy solution to Solo.io's Gloo API Gateway.
     * Fully manage the whole platform, from the infrastructure to the business apps through the CI/CD, with Terraform/GitlabCI/ArgoCD/Kustomize using a commmon codebase.
     * Secured GCP/GKE platform by banishing static credentials (GKE workload identity up to production), introduced private GKE clusters.
     * Currently working on Open Policy Agent business rules coupling with Kubernetes Service Meshes, and dynamic Vault secrets.

* *2017-2020* **Malt Community / Platform Tech Lead**
    * **Milestones**:
      * Planned and realized the migration of Malt's applications and databases from a bare metal infrastructure to Google Cloud Platform (GCE and GKE).
      * Progressively migrated the Ansible historical codebase to a Terraform-managed codebase.
      * Implemented CI/CD for the infrastructure side of things using Gitlab pipelines.
      * Automated and secured all internal application traffic using short-lived dynamic certificates from Hashicorp Vault PKI.
      * Implemented GitOps continuous delivery flows for every Malt application using ArgoCD.
      * Integrated Vault as a secure Spring configuration server for every Spring application.
      * Worked continuously with the security team to achieve optimal DevSecOps practices.
      * Introduced high availability features on all applications (Spring Boot) and databases (MongoDB, Elasticsearch, Redis) using Hashicorp Consul.
      * Java 8+11 applications G1GC ideal performance tuning for Kubernetes.

* *2014-2017* **Sogelink / Sysadmin**
  * **Milestones**:
    * Implemented a highly available centralized logging solution using Graylog.
    * Worked closely with developers on ActiveMQ broker clustering.
    * Created the company's technical Disaster Recovery plan.
    * Oversaw and executed the migration of the company's production data (>200TB) on Hitachi VSP SAN multi site appliances.
* *2013-2014* **Armée de Terre / Officer**
* *2010-2013* **Armée de Terre / Telecommunications specialist**

---

### Education

* *2009* [Telecom Sud Paris](https://www.telecom-sudparis.eu/) / Engineering
* *2006* CPGE Mathematics Lycée Chaptal Saint-Brieuc

---

### Publications

*2019*
  * [DevOps — Retour sur un downtime Redis, Kubernetes en production](https://medium.com/nerds-malt/https-medium-com-nerds-malt-devops-retour-sur-un-downtime-redis-kubernetes-en-production-8cd5bfcc53d) (French)
  * [A GCP / Kubernetes production migration retrospective](https://medium.com/nerds-malt/a-gcp-kubernetes-production-migration-retrospective-part-1-e3e35096073a)

---

### Open source contributions

*2020*
  * [terraform-provider-argocd (Go)](https://github.com/oboukili/terraform-provider-argocd)

*2019*
  * [Vault Discovery (Go)](https://github.com/oboukili/vault-discovery)
  * [Vault KV updater (Go)](https://github.com/oboukili/vault-kv-updater)
  * [Kustomize Checksumer Plugin (Go)](https://github.com/oboukili/checksumer)
  * [Kustomize SopsDecoder Plugin (Go)](https://github.com/oboukili/sopsdecoder)

*2016*
  * [Ansible apache2_mod_proxy module (Python)](https://docs.ansible.com/ansible/latest/modules/apache2_mod_proxy_module.html)
