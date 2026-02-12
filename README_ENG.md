# Survey service 

## Business overview
### Purpose
The service allows users to conduct surveys. There are three participants roles: 
- service owner, 
- survey creator, 
- respondent. 

Definitions: 
- **Service owner** - person or organization that provides the platform to create surveys as a service. 
- **Survey creator** - user of a service, that create survey(s) with goal to collect responses for analysis.
- **Respondent** - the person who answers the questions of survey.
- **Service** — a network-accessible application that provides functionality to clients over the Internet and exposes an API for integration. 

## Technical overview
The Survey Service is implemented as a Spring Boot application.

The application: 
- Exposes RESTfull APIs
- Implements business logic for survey lifecycle management
- Persists data in a relational and document databases
- Is packaged as a container image

### Deployment model
The service is containerized and supports deployment in: 
- A standalone container runtime (Docker)
- Kubernetes (as a Deployment resource that manages Pods)
- A cloud-based container platform

## Roadmap
| # | Stage                      | Finish Date | Description                                                      |
|---|----------------------------|-------------|------------------------------------------------------------------|
| 1 | Requirements               | 13 Feb 2026 | Business requirements and use cases                              |
| 2 | Architecture of the system | 13 Feb 2026 | Definition of the system`s components                            |
| 3 | Data model                 | 16 Feb 2026 | Relational data model of survey management system in CF notation |
| 4 | API                        | 17 Feb 2026 | API described using OpenAPI Specification                        |
| 5 | Implementation             | 18 Feb 2026 | Estimation of time required to implement the system              |

