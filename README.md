# 🔐 Yandex Cloud Security Solution Library
**Yandex Cloud Security Solution Library** — это набор примеров и рекомендаций, собранных в публичных репозиториях на GitHub. Они помогут компаниям, которые хотят построить безопасную инфруструктуру в Yandex Cloud и соответствовать требованиям различных регуляторов и стандартов.
Команда Yandex Cloud проработала самые распространённые задачи, которые возникают при построении безопасности в облаке, протестировала и подробно описала необходимые сценарии.

#### Вводный вебинар 
[![image](https://user-images.githubusercontent.com/85429798/146542425-b250c494-9a3c-4744-897d-5f65849355d5.png)](https://www.youtube.com/watch?v=WZOB9ow0WrA)


#### ☑️ Стандарт по защите облачной инфраструктуры Yandex Cloud 1.1
Чеклист по безопасности в облачной инфраструкутре Yandex Cloud:

[https://cloud.yandex.ru/docs/security/standard/all](https://cloud.yandex.ru/docs/security/standard/all)

# Список решений
- 🕸 Сетевая безопасность
  - [Пример организации site-to-site VPN соединений к Yandex Cloud на основе IPsec с помощью решения StrongSwan ](https://github.com/yandex-cloud-examples/yc-site-to-site-vpn-with-ipsec-strongswan)
  - [Пример создания remote-acess VPN соединений к Yandex Cloud на основе Wireguard с помощью решения Firezone](https://github.com/yandex-cloud-examples/yc-remote-acess-vpn-with-wireguard-firezone)
- 🔑 Аутентификация и управление доступом
  - [Развёртывание федерации удостоверений в Yandex Cloud на базе решения Keycloak](https://github.com/yandex-cloud-examples/yc-iam-federation-with-keycloak-vm)
- 🦠 Защита от вредоносного кода
  - [Развертывание Kaspersky Antivirus в Yandex Cloud (Compute Instance, COI)](https://github.com/yandex-cloud-examples/yc-kasperksy-antivirus-deploy)
- 🐞 Управление уязвимостями
  - [Отказоустойчивая эксплуатация PT Application Firewall в Yandex Cloud](https://github.com/yandex-cloud-examples/yc-webinar-pt-application-firewall-ha-operations)
  - [Тестирование AntiDDos системы с помощью Yandex Load Testing](https://github.com/yandex-cloud-examples/yc-load-testing-for-dos-simulation)
- 🔏 Шифрование данных и управление ключами/секретами
  - [Шифрование секретов средствами KMS при передачи их в контейнер ВМ на базе Container Optimized Image (COI) в Yandex Cloud](https://github.com/yandex-cloud-examples/yc-encrypt-coi-secrets)
  - [Шифрование диска ВМ в Облаке с помощью YC KMS](https://github.com/yandex-cloud-examples/yc-encrypt-vm-disk-with-kms)
  - [Vault-to-Lockbox Migrator](https://github.com/yandex-cloud-examples/yc-lockbox-migration-from-hashicorp-vault)
  - [Lockbox Безопасная передача паролей в Windows](https://github.com/yandex-cloud-examples/yc-secure-bypass-password-to-cloudinit)
  - [Использование Lockbox для получения паролей в VM](https://github.com/yandex-cloud-examples/yc-lockbox-for-keycloak-vm)
- 🔎 Сбор, мониторинг и анализ аудит логов
  - [Сбор, мониторинг и анализ аудит логов Yandex Cloud в Yandex Managed Opensearch](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-opensearch)
  - [Сбор, мониторинг и анализ аудит логов в Yandex Managed Service for Elasticsearch (ELK)](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-elk)
  - [Сбор, мониторинг и анализ аудит логов во внешний SIEM ArcSight](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-arcsight)
  - [Сбор, мониторинг и анализ аудит логов во внешний Splunk](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-splunk)
  - [Сбор, мониторинг и анализ аудит логов во внешний Wazuh](https://github.com/yandex-cloud-examples/yc-export-auditlogs-to-wazuh)
  - [Trails-function-detector: Оповещения и реагирование на события ИБ Audit trails с помощью Cloud Logging/Cloud Functions + Telegram](https://github.com/yandex-cloud-examples/yc-audit-trails-automatic-response)
  - [Мониторинг Audit Trails и событий в Yandex Cloud Monitoring](https://github.com/yandex-cloud-examples/yc-audit-trails-monitoring)

- 👮 Безопасная конфигурация
  - [Пример безопасной конфигурации Yandex Cloud Object Storage: Terraform](https://github.com/yandex-cloud-examples/yc-s3-secure-bucket)
  - (Скоро) запрет доступа к метадате

##
<a href="https://kubernetes.io/">
    <img src="https://github.com/kubernetes/kubernetes/blob/master/logo/logo.svg"
         alt="Kubernetes logo" title="Kubernetes" height="50" width="50" />
</a><br>

- Безопасность Kubernetes
  - Аутентификация и управление доступом Managed Kubernetes:
    - [Пример настройки ролевых моделей и политик в Managed Service for Kubernetes](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/auth_and_access/role-model-example/README_RU.md)
  - Сбор, мониторинг и анализ аудит логов:
    - [Анализ логов безопасности k8s в ELK: аудит-логи, policy engine, falco](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/auditlogs/export-auditlogs-to-ELK_k8s)
    - [Экспорт Cilium Flow Logs в Object Storage(s3)](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/auditlogs/cilium-s3)
    - [Экспорт k8s аудит логов в s3/object storage](https://github.com/yandex-cloud/yc-solution-library-for-security/blob/master/auditlogs/export-k8s-to-s3/README.md)
    - [Экспорт k8s аудит логов в Yandex Data Streams/Kinesis Data Streams](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/auditlogs/export-k8s-to-yds)
  - Шифрование данных и управление ключами/секретами Managed Kubernetes
    - [Управление секретами c SecretManager(Lockbox,Vault)](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/encrypt_and_keys/secret-management/README_RU.md)
  - Безопасная конфигурация Managed Kubernetes:
    - [osquery и kubequery в k8s: osquery (защита k8s nodes), kubequery (анализ конфиг. всего k8s) ](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/osquery-kubequery/README_RU.md)
  - [Интеграция Starboard с Yandex Cloud Container Registry с целью сканирования запущенных образов](https://github.com/yandex-cloud/yc-solution-library-for-security/tree/master/kubernetes-security/starboard_and_yc-cr/README_RU.md)

##
<a href="https://kubernetes.io/">
    <img src="https://logowik.com/content/uploads/images/gitlab8368.jpg"
         alt="Kubernetes logo" title="Kubernetes" height="50" width="50" />
</a></br>

- CI/CD Security
  - Secure CI/CD на базе Managed GitLab:
    - [Вебинар+материалы:Обнаружение Log4shell и др. уязвимостей в CI/CD на базе Managed GitLab](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab):
      - [Обнаружение уязвимостей в CI/CD (Ultimate лицензия)](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab)
      - [Обнаружение уязвимостей в CI/CD (Free лицензия)](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab)
      - [Security in Gtilab instance check-list](https://github.com/yandex-cloud-examples/yc-webinar-secure-cicd-with-gitlab/tree/main/gitlab_instance_sec_checklist)
  - [Выступление про комплаенс и devsecops](https://github.com/yandex-cloud-examples/yc-webinar-devsecops-compliance-2022) 

##
<a href="https://kubernetes.io/">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Telegram_2019_Logo.svg/1200px-Telegram_2019_Logo.svg.png"
         alt="Kubernetes logo" title="Kubernetes" height="50" width="50" />
</a><br>


# Обратная связь и пожелания
- Доработки, ошибки, contribute - с помощью инструментов Github - [Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) и [Pull Requests (PR)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
- Вопросы, пожелания, консультации: Пишите нам в телеграм https://t.me/YandexCloudSecurity

#### Референсная архитектура
![Refer_arc](https://user-images.githubusercontent.com/85429798/132501079-0bd89876-2cc9-405b-aac3-ea65ac1fb6d2.png)
