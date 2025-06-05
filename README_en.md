# 🔐 Yandex Cloud Security Solution Library
**Yandex Cloud Security Solution Library** is a collection of examples and tips residing in public GitHub repositories. Its purpose is to help companies build a secure infrastructure in Yandex Cloud and meet the requirements of various regulators and standards.
The Yandex Cloud team has selected the most common tasks that arise when building security in the cloud. They have tested and described relevant scenarios in detail.

#### Introductory webinar 
[![image](https://user-images.githubusercontent.com/85429798/146542425-b250c494-9a3c-4744-897d-5f65849355d5.png)](https://www.youtube.com/watch?v=WZOB9ow0WrA)


#### ☑️ Standard for securing Yandex Cloud infrastructure 1.1
Checklist for security in the Yandex Cloud infrastructure:

[https://yandex.cloud/docs/security/standard/all](https://yandex.cloud/docs/security/standard/all)

# List of solutions
- 🕸 Network security
  - [Example of setting up an IPsec-based site-to-site VPN connection to Yandex Cloud using strongSwan](https://github.com/yandex-cloud-examples/yc-site-to-site-vpn-with-ipsec-strongswan)
  - [Example of setting up a Wireguard-based remote-access VPN connection to Yandex Cloud using Firezone](https://github.com/yandex-cloud-examples/yc-remote-acess-vpn-with-wireguard-firezone)
- 🔑 Authentication and access management
  - [Deploying an identity federation in Yandex Cloud using Keycloak](https://github.com/yandex-cloud-examples/yc-iam-federation-with-keycloak-vm)
- 🦠 Protection against malicious code
  - [Deploying Kaspersky Antivirus in Yandex Cloud (Compute Instance, COI)](https://github.com/yandex-cloud-examples/yc-kasperksy-antivirus-deploy)
- 🐞 Managing vulnerabilities
  - [Fault-tolerant operation of PT Application Firewall in Yandex Cloud](https://github.com/yandex-cloud-examples/yc-webinar-pt-application-firewall-ha-operations)
  - [Testing an anti-DDos solution with Yandex Load Testing](https://github.com/yandex-cloud-examples/yc-load-testing-for-dos-simulation)
- 🔏 Encrypting data and managing keys/secrets
  - [Encrypting secrets with KMS when transferring keys to a VM container built on Container Optimized Image (COI) in Yandex Cloud](https://github.com/yandex-cloud-examples/yc-encrypt-coi-secrets)
  - [Encrypting a VM disk in Yandex Cloud using YC KMS](https://github.com/yandex-cloud-examples/yc-encrypt-vm-disk-with-kms)
  - [Vault-to-Lockbox Migrator](https://github.com/yandex-cloud-examples/yc-lockbox-migration-from-hashicorp-vault)
  - [Lockbox: Safely transmitting passwords in Windows](https://github.com/yandex-cloud-examples/yc-secure-bypass-password-to-cloudinit)
  - [Using Lockbox to get passwords within a VM](https://github.com/yandex-cloud-examples/yc-lockbox-for-keycloak-vm)
- 🔎 Collecting, monitoring, and analyzing audit logs
  - [Collecting, monitoring, and analyzing Yandex Cloud audit logs in Yandex Managed OpenSearch](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-opensearch)
  - [Collecting, monitoring, and analyzing audit logs in Yandex Managed Service for Elasticsearch (ELK)](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-elk)
  - [Collecting, monitoring, and analyzing audit logs in the external ArcSight SIEM](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-arcsight)
  - [Collecting, monitoring, and analyzing audit logs in the external Splunk solution](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-splunk)
  - [Collecting, monitoring, and analyzing audit logs in the external Wazuh solution](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-wazuh)
  - [Trails-function-detector: Notifying and responding to Audit Trails information security events using Cloud Logging/Cloud Functions + Telegram](https://github.com/yandex-cloud-examples/yc-audit-trails-automatic-response)
  - [Monitoring Audit Trails and events in Yandex Cloud Monitoring](https://github.com/yandex-cloud-examples/yc-audit-trails-monitoring)

- 👮 Secure configuration
  - [Example of a secure configuration for Yandex Cloud Object Storage: Terraform](https://github.com/yandex-cloud-examples/yc-s3-secure-bucket)
  - _(Coming soon)_ Denying access to metadata

<p align="left">
    <img src="https://github.com/kubernetes/kubernetes/blob/master/logo/logo.svg" alt="Kubernetes logo" width="50"/>
</p>

- Kubernetes security
  - Authentication and access management in Managed Kubernetes:
    - [Example of setting up role-based models and policies in Yandex Managed Service for Kubernetes](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/auth_and_access/role-model-example/README_RU.md)
  - Collecting, monitoring, and analyzing audit logs:
    - [Analyzing K8s security logs in ELK: audit logs, policy engine, falco](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/auditlogs/export-auditlogs-to-ELK_k8s)
    - [Exporting Cilium Flow Logs to Object Storage (S3)](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/auditlogs/cilium-s3)
    - [Exporting K8s audit logs to S3 / Object Storage](https://github.com/yandex-cloud/yc-solution-library-for-security/blob/master/auditlogs/export-k8s-to-s3/README.md)
    - [Exporting K8s audit logs to Yandex Data Streams / Kinesis Data Streams](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/auditlogs/export-k8s-to-yds)
  - Encrypting data and managing keys/secrets in Managed Kubernetes
    - [Managing keys with SecretManager (Lockbox, Vault)](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/encrypt_and_keys/secret-management/README_RU.md)
  - Secure configuration of Managed Kubernetes:
    - [Osquery and Kubequery in K8s: Osquery (protecting K8s nodes), Kubequery (analyzing the configuration of the entire K8s)](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/osquery-kubequery/README_RU.md)
  - [Integrating Starboard with Yandex Cloud Container Registry to scan running images](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/starboard_and_yc-cr/README_RU.md)

<p align="left">
    <img src="https://logowik.com/content/uploads/images/gitlab8368.jpg" alt="Gitlab logo" height="50" width="50"/>
</p>

- CI/CD Security
  - Secure CI/CD using Managed GitLab:
    - [Webinar and materials: Detecting Log4shell and other vulnerabilities in CI/CD using Managed GitLab](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab):
      - [Detecting vulnerabilities in CI/CD (Ultimate edition)](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab)
      - [Detecting vulnerabilities in CI/CD (Free edition)](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab)
      - [Security in Gtilab instance check-list](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab/tree/main/gitlab_instance_sec_checklist)
  - [Discussing compliance and DevSecOps](https://github.com/yandex-cloud-examples/yc-webinar-devsecops-compliance-2022)
  - [Webinar and materials: How to arrange a secure development workflow in Yandex Cloud](https://github.com/yandex-cloud-examples/yc-webinar-security-pipeline-2023)

<p align="left">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/1200px-Telegram_2019_Logo.svg.png" alt="Telegram logo" width="50"/>
</p>

# Your feedback and suggestions
- For improvements, bugs, or contributions, use GitHub tools: [Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) and [Pull Requests (PRs)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
- Have any questions or suggestions, or need advice? [Telegram us](https://t.me/YandexCloudSecurity).

#### Reference architecture
![Refer_arc](https://user-images.githubusercontent.com/85429798/132501079-0bd89876-2cc9-405b-aac3-ea65ac1fb6d2.png)
