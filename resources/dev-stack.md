# Creator X Application

> This is Is development documentation for the development of the Creator X Application

- [ ] Stack Overview
- [ ] Postgres
- [ ] Auth schemas
- [ ] user data schemas
- [ ] ML data schemas
- [ ] Keycloak
- [ ] JWT
- [ ] React
- [ ] Fast API
- [ ] NestJS
- [ ] GraphQL
- [ ] Express

---
## Stack Overview

The following is the architectural layout of the application:

### Front End
The frontend utilizes React and Node JS

### BackEnd
Backend service are isolated and comprised of GraphQL for internal user data, REST API with NestJS for type safe persistence API layer, and FastAPI for ML and AI models.

### Auth
Keycloak is the SSO and ID management utility for authorization and access and JWT for encrypted security

### Data Persistence
Postgres is the database chosen because of its versatility and ability to handle transactional data and JSON documents



### TODO
- []  add  Redis for in memory key store
- [] Build Design kit
- [] Front end models
- [] link resources.

