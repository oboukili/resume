# Olivier Boukili / Senior Cloud Architect

---

*Je suis "DevOps" et architecte cloud.
J'ai 11 ans d'expérience en tant qu'administrateur système et cloud engineer, dont 7 ans pendant lesquelles j'ai travaillé pour des startups et scale-ups.*

*J'ai eu l'opportunité d'acquérir de l'expérience en architecture sur des plateformes Cloud majeures comme Google Cloud Platform (GCP), avec un focus particulier sur les plateformes de conteneurs Linux (GKE / Kubernetes) et serverless (GCP Cloud Run, GCP Cloud Functions), et d'avoir implémenté et géré jusqu'en production des services techniques à forte valeur ajoutée telles que des API Gateways (solo.io Gloo), la suite Hashicorp (Vault, Consul), ainsi que des plateformes d'intégration/déploiement continus (Gitlab, ArgoCD, Github Actions, CircleCI), en utilisant des outils adaptés et faciles à maintenir et à étendre via le biais de contributions opensource Go/Golang (providers Terraform, plugins Kustomize, contributions ArgoCD, charts Helm ..).*

*Très sensible à la performance et à la haute disponibilité applicative, je travaille systématiquement avec les équipes de développement pour prévoir, détecter, analyser et résoudre ce type de problématique.*

*Je m'evertue à rendre accessibles, à rendre pèrennes, et à documenter toutes les solutions d'automatisation que je mets en place. Et surtout à communiquer avec l'ensemble des équipes de développeurs, SRE, ou platform engineers en promouvant une ambiance sympathique, et agréable, comme le définirait la culture "devops" ;) !*

---

### Certifications

* Google Cloud Professional Architect certification (01/2021)

### Stacks techniques


**Cloud Providers**
* Google Cloud Platform
* AWS

**Services**
* Kubernetes
* Google Cloud Run
* Linkerd 2 Service Mesh
* Vault
* ArgoCD
* Consul
* Traefik
* Prometheus
* Sensu
* Gloo API Gateway
* Jaeger Opentracing

**Langages**
* Go
* Python

**Outils:**
* GoLand IDE
* Terraform
* Kustomize
* Gitlab
* Github
* CircleCI
* Ansible

---

## Experiences

### *2021* **DoiT International / Senior Cloud Architect**

  * Missions de consulting en architecture Cloud GCP/AWS à des clients globaux.
  * Contexte international.

### *2021* **Wanteeed / Cloud Architect**

| Technos:
  * Google Cloud Run Fully Managed
  * Github Actions / CircleCI
  * Terraform
  * Cloudflare

| Milestones:
  * Mission de conseil en architecture cloud et monitoring GCP et implémentation 100% infra-as-code du pipeline CI/CD d'infrastructure Cloudflare/GCP avec Terraform.


### *2020* **Sun'R / Cloud Architect**

| Technos:
  * Scaleway Cloud Provider
  * Kubernetes / Kapsule
  * Traefik
  * Terraform / Kustomize

| Milestones:
  * Mission de conseil et formation en architecture cloud public et Kubernetes à des fins de prévention de problématiques de montée en charge de trafic et de maintenance.

### *2020* **Keplr / Cloud Engineer**

| Technos:  
  * Cloud: Google Cloud Platform, Kubernetes, Cloud Run, Linkerd2 Service Mesh
  * Services: Hashicorp Vault, solo.io Gloo API Gateway
  * Continuous Integration/Deployment: GitlabCI, ArgoCD, Github Actions, CircleCI
  * Outils: Terraform, Kustomize, Helm
  * Bases de données: PostgreSQL, MongoDB, Redis
  * Documentation: HuGo, MermaidJS
  * Monitoring: Google Stackdriver, Grafana
  * Développement: Go

| Milestones: 
  * Import et management "as code" complet de l'infrastructure existante avec Terraform, ArgoCD, et Kustomize.
  * Création du self-service DevOps CI/CD avec Gitlab CI et ArgoCD, permettant aux équipes produit de deployer rapidement de nouvelles applications jusqu'en production de manière autonome.
  * Mise en place d'une CI Gitlab + Kubernetes avec "autoscaling" dynamique suivant la demande pour minimiser le "time-to-market" et réduire les coûts.
  * Utilisation de solo.io Gloo API Gateway pour permettre des stratégies avancées de routing microservices (délégation de routes, environnements éphémères, tests fault injection...)
  * Généralisation de l'utilisation de secrets dynamiques "à la demande", expirant dans le temps, pour l'accès aux bases de données pour l'ensemble des applications du parc via Hashicorp Vault.
  * Contributions open source Go: Gitlab CI runner, Terraform provider Gitlab, Terraform provider ArgoCD.


### *2017-2020* **Malt Community / Platform Tech Lead**

| Technos
  * Cloud: Google Cloud Platform, Kubernetes, OVH, Scaleway
  * Services: Traefik, Nginx, Hashicorp Vault, Hashicorp Consul, RabbitMQ
  * Continuous Integration/Deployment: Jenkins, Bamboo, GitlabCI, ArgoCD
  * Outils: Terraform, Kustomize, Ansible, Packer
  * Documentation: Mkdocs
  * Bases de données: PostgreSQL, MongoDB, Redis, Elasticsearch, InfluxDB
  * Monitoring: Sensu, Prometheus, Telegraf, Grafana
  * Développement: Go


| Milestones:
  * Mise en place d'une PKI TLS automatisée avec Hashicorp Vault pour sécuriser, identifier, et authentifier les applications Java Spring Boot métier entre elles et les bases de données.
  * Intégration de Hashicorp Vault en qualité de serveur de configuration Spring Boot.
  * Migration de l'ancienne infrastructure bare-metal/Openstack OVH vers GCP/Kubernetes (GKE)
  * "Service Discovery" avec Consul + Spring Cloud Consul sur une infrastructure bare-metal OVH.
  * APM et outils de tracing (GlowRoot, Jaeger, ...)
  * Management 100% infra-as-code de l'infrastructure Terraform, ArgoCD, et Kustomize.
  * Tuning de performance Java 8+11/12 (G1GC/Shenandoah GC), optimisations spécifiques Java avec Docker/Kubernetes.
  * Contributions open source Go: plugins Kustomize, utilitaires Go.


### *2014-2017* **Sogelink / Sysadmin**

| Technos
  * Infrastructure/Compute: Dell Proliant (multiples datacenters)
  * Infrastructure/Virtualisation: VMWare ESXi, Xen
  * Infrastructure/Stockage: SANs Hitachi VSP2xx
  * Infrastructure/Réseau: Fortinet firewalls, switches FiberChannel/ethernet HP
  * Services: Asterisk VOIP, Apache2 proxy, ActiveMQ
  * Continuous Integration/Deployment: Gitlab CI, Jenkins
  * Outils: Ansible, Puppet, SaltStack
  * Bases de données: PostgreSQL, MongoDB, Redis, Solr, Elasticsearch, KahaDB
  * Monitoring: Nagios, Graylog
  * Développement: Python
  * Contributions open source Python: module Ansible apache2_mod_proxy

| Milestones:
  * Migration des scripts Puppet à Ansible
  * Création du PRA (plan de reprise d'activité) technique de l'entreprise
  * Astreintes 24/24H 7j/7
  * Mise à niveau majeure VMWare ESXi sans downtime
  * Benchmark de performances IO de solutions de stockage (baies SAN Hitachi, Dell / stockage distribué Ceph)
  * Migration sans downtime de baies de stockage sur 2 sites distincts
  * Création d'une plateforme de logging avec Graylog et Elasticsearch

---

### Formation

* *2009* [Telecom Sud Paris](https://www.telecom-sudparis.eu/) / Cursus Ingénieur
* *2006* CPGE Maths sup/spé TSI Lycée Chaptal Saint-Brieuc

---

---

### Publications

*2019*
* [DevOps — Retour sur un downtime Redis, Kubernetes en production](https://medium.com/nerds-malt/https-medium-com-nerds-malt-devops-retour-sur-un-downtime-redis-kubernetes-en-production-8cd5bfcc53d) 
* [A GCP / Kubernetes production migration retrospective](https://medium.com/@boukili.olivier/a-gcp-kubernetes-production-migration-retrospective-part-1-e3e35096073a)

---

### Open source contributions

*2021*
* [pdb-pods-owner-discovery (Go)](https://github.com/oboukili/pdb-pods-owners-discovery)

*2020*
* [terraform-provider-argocd (Go)](https://registry.terraform.io/providers/oboukili/argocd/latest)
* [gitlab-runner Kubernetes (Go)](https://gitlab.com/gitlab-org/gitlab-runner/-/merge_requests/2117)
* [terraform-provider-gitlab (Go)](https://github.com/gitlabhq/terraform-provider-gitlab/)

*2019*
* [Vault Discovery (Go)](https://github.com/oboukili/vault-discovery)
* [Vault KV updater (Go)](https://github.com/oboukili/vault-kv-updater)
* [Kustomize Checksumer Plugin (Go)](https://github.com/oboukili/checksumer)
* [Kustomize SopsDecoder Plugin (Go)](https://github.com/oboukili/sopsdecoder)

*2016*
* [Ansible apache2_mod_proxy module (Python)](https://docs.ansible.com/ansible/latest/modules/apache2_mod_proxy_module.html)
