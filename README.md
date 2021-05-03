# iianian-ecom project: Express + Angular + TypeORM/MySql + TypeScript

Final project with Open Source JS modern tech stack. It provides common and nessary features of a standard eCommerce website.

iianian-ecom come with 3 part:

- iianian-ecom Restful API.
- iianian-econ Admin Control Panel.
- iianian-ecom Store Front.

<img  src='./images/reports/ArchitectureOverview.png' style="max-width:800px" alt='api-architect'/>

| Reference | URL                                                   |
| --------- | ----------------------------------------------------- |
| API       | https://github.com/lamhungypl/iianian-ecom-api        |
| Admin     | https://github.com/lamhungypl/iianian-ecom-admin      |
| Storefont | https://github.com/lamhungypl/iianian-ecom-storefront |

# ❯ API Design

## Logic layers

<img  src='./images/reports/api/API-Architecture.png' style="max-width:800px" alt='api-architect'/>

- Model
- Repository
- service
- Controller
- Auth Guard
- ErrorHandler
- Logging

## Database

Simplify table design

<img src='./images/reports/api/iianian-ecom-erd.png' style="max-width:800px" alt='api-architect'/>

## API Docs

[Sample API Docs](https://lamhungypl.github.io/iianian-ecom/public/apidoc/index.html)

# ❯ Frontend Architecture

## Logic layer

<img  src='./images/reports/frontend/angular-architecture.jpg' style="max-width:800px" alt='api-architect'/>

- Configuration
- Business

  Core function with Redux Store.

<img  src='./images/reports/frontend/state-management-lifecycle.png' style="max-width:800px" alt='api-architect'/>

- Intermediate
- Representation

## User Interface

- Admin UI

<img  src='./images/reports/frontend/Admin-site-map.png' style="max-width:800px" alt='api-architect'/>

<img  src='./images/reports/frontend/admin-dashboard.png' style="max-width:800px" alt='api-architect'/>

- Storefront UI

<img  src='./images/reports/frontend/store-site-map.png' style="max-width:800px" alt='api-architect'/>

<img  src='./images/reports/frontend/store-homepage.png' style="max-width:800px" alt='api-architect'/>
