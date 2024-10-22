# Technical stack in use

- **Author:** Rainer Türner
- **Date:** 22.10.2024
- **Version:** 1.0.0
- **Status:** Draft
- **Last Updated:** N/A
- **Reviewed By:** N/A
- **Approvers:** Rainer Türner

---

## Change Log
| Version | Date       | Author     | Description                           |
|---------|------------|------------|---------------------------------------|
| 1.0.0   | 2024-10-22 | Rainer Türner     | Initial document creation             |


```mermaid
timeline
    title Technical stack in use

    section In-house developments
        Java    :   Ruuter
                :   Resql
                :   TIM
                :   XTR
        React   :   Chat Widget
                :   Backoffice GUI
        Based on external libraries :   Data Mapper<br>(handlebarsjs.com)
        Based on Bükstack   :   Backoffice back-end
                            :   Notification service

    section Third-party components
        Web servers :   Nginx
        Data storage    :   Postgres
                        :   OpenSearch
                        :   S3
                        :   File storage on PV
        NLP :   Rasa
    
    section Third-party
        Libraries   :   Liquibase
        Services    :   TARA
                    :   X-Road
        SaaS        :   Azure AI Studio (gpt-4o)
    
    section Deployment
        Version control :   GitHub (github.com/buerokratt)
                        :   GitHub Package Registry
        Orchestration   :   GitHub Actions
                        :   Kubernetes
        Platforms       :   Estonian Government Cloud
                        :   RIA on-prem
```
