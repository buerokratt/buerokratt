# Bürokratt's Test-Driven Development roadmap

- **Author:** Rainer Türner
- **Date:** 10.10.2024
- **Version:** 1.0.0
- **Status:** Draft
- **Last Updated:** N/A
- **Reviewed By:** Markko Liutkevicius
- **Approvers:** Rainer Türner, Markko Liutkevicius

---

## Change Log
| Version | Date       | Author     | Description                           |
|---------|------------|------------|---------------------------------------|
| 1.0.0   | 2025-10-10 | Rainer Türner     | Initial document creation             |


```mermaid
timeline
    title Bürokratt's Test-Driven Development roadmap for Q4/2024

    section October
        Manual E2E tests    :   Existing Chat Widget covered
                            :   Existing Backoffice/Chat covered
                            :   Existing Backoffice/Settings covered
                            :   Existing Backoffice/Training Module covered
                            :   Existing Backoffice/Analytics covered
        Automatic E2E test generation   :   DSL for visibility tests confirmed
                                        :   POC for visibility tests working
        API endpoints   :   List API endpoints as OpenAPI specs
        Automatic validation    :   All existing tests run periodically
                                :   Test reports generated automatically for in-house use
    
    section November
        Manual E2E tests    :   Existing Backoffice/Service Module covered
                            :   New Backoffice/Service Module covered
        Automatic E2E test generation    :   Chat Widget visibility tests covered
                            :   Backoffice/Chat visibility tests covered
                            :   Backoffice/Settings visibility tests covered
                            :   Backoffice/Training Module visibility tests covered
                            :   Backoffice/Service Module visibility tests covered
                            :   Backoffice/Analytics visibility tests covered
                            :   DSL for functionality tests confirmed
                            :   POC for functionality tests working
        API endpoints   :   All API endpoints published as OpenAPI specs
        Automatic validation    :   All existing tests run periodically
                                :   Test reports generated automatically and published in public
                                :   Tests triggered on code commit
                                :   Bugs reported automatically as GitHub tasks
    
    section December
        Automatic E2E test generation    :   Chat Widget functionality tests covered
                            :   Backoffice/Chat functionality tests covered
                            :   Backoffice/Settings functionality tests covered
                            :   Backoffice/Training Module functionality tests covered
                            :   Backoffice/Service Module functionality tests covered
                            :   Backoffice/Analytics functionality tests covered
        API endpoints   :   All API endpoints covered with automatic tests
        Automatic validation    :   All existing tests run periodically
                                :   Test reports generated automatically and published in public
```
