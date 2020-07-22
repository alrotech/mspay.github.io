# MS Payments Project

Overall high-level description of the project. Some parts of documentation and descriptions may be placed to appropriate repositories. This repository represents the public part of the entire project. Generated copy of this documentation available on the website [about.mspay.by](https://about.mspay.by) or [mspay.github.io](https://mspay.github.io) (if original domain by any reason will be lost).

## Development Process

Development process and work in general under the project base on Agile principals but are not fully covered. We are using **Projects**, **Epics**, **User Stories** to describe tasks, that should be done. These terms were adopted a bit to have the ability to use them via built-in tools, that GitHub provides.

That means that we use GitHub Projects for describing [the projects](#Projects), by Agile it is a replacement for _Initiatives_. **Epics** are done via _milestones_ with or without setting the date of end. From an Agile perspective, it may look strange, but the main goal to show real state and progress at any time. **User Stories** are usual _Issues_.

Roles for user stories not strictly defined, it based on the context of usage. In case of a technical story, the role may be a developer, if we a describing user experience, it may be a customer or author of extra, etc.

## Projects

Projects on GitHub works as Initiatives from Agile methodology and combine inside all work, related to the goal, that should be reached. The project is an overall piece of work, unrelated to any repository, service, or any other things. The task in the project can include work under code, documentation stuff, dealing with the authorities, etc.

The most important goal of project to provide visibility of the progress of the work. How much should be done, what left to implement and solve, how far from or close to the finish we are.

Below is a list of active projects with their short descriptions. Follow the links to see the progress of each and see all linked repositories.

### [Payment Gateways][prj1]
Work that is related to extensions for payment gateways.

### [Package Builder][prj4]
Development tools for generating MODX-compatible packages.

### [Users and Roles][prj2]
Managing users, roles, scopes, authorization and authentication, JWT-processing and other related to users and their accounts work.

- [Basic App and API Structure][data-1]
- [Users, Roles and Scopes][data-2]
- [JWT Auth Implementation][data-3]
- [User Management UI][admin-1]
- [User Account UI][client-1]

### [Packages and Versions][prj5]
Managing, uploading, updating and building the packages and their versions.

- Packages and Versions models
- UI for package management
- Pulic package listing

### [Licenses and Protection][prj6]
Managing licenses, packs of licenses, access keys, and all that replated to packages protection, including encryption.

### [Billing and Payments][prj3]
All work that is related to receiving money. Integration of payment system, setting prices and subscriptions, handling cashless payments.

- UI for account payment information

### [Support Area][prj7]
Managing all customer's requests for any reason.

- Tickets models and structure (api)
- UI for tickets management (admin)
- UI for tickets creating (client)

## Services

Service usually is live environment, available for end-users. As well, based on the context of usage, service may mean a staging/testing environment or repository with a code of service. Below presented matrix of services and their sources and instances.

Name | Links | Description
---|---|---
Data | [Live](https://api.mspay.by) / [Test](https://mspay-api.herokuapp.com/) / [Repo](https://github.com/mspay/service-api) | Backend API for marketplace 
Langing | [Live](https://mspay.by) / [Test](https://mspay.netlify.app) / [Repo](https://github.com/mspay/service-langing) | The main website of the payment solutions service
Extras | [Live](https://extras.mspay.by) / [Test]() / [Repo](https://github.com/mspay/service-extras) | Repository REST service for MODX, based on Slim Framework
Admin | [Live](https://manage.mspay.by) / [Test](https://cpmspay.netlify.app/) / [Repo](https://github.com/mspay/service-admin) | Admin dashboard. While development, it uses a temporary name and hosted on the Netlify
Client | [Live](https://client.mspay.by) / [Test](https://lkmspay.netlify.app/) / [Repo](https://github.com/mspay/service-client) | Client dashboard. While development, it uses a temporary name and hosted on the Netlify

[prj1]: https://github.com/orgs/mspay/projects/1
[prj2]: https://github.com/orgs/mspay/projects/2
[prj3]: https://github.com/orgs/mspay/projects/3
[prj4]: https://github.com/orgs/mspay/projects/4
[prj5]: https://github.com/orgs/mspay/projects/5
[prj6]: https://github.com/orgs/mspay/projects/6
[prj7]: https://github.com/orgs/mspay/projects/7

[data-1]: https://github.com/mspay/service-api/milestone/1
[data-2]: https://github.com/mspay/service-api/milestone/2
[data-3]: https://github.com/mspay/service-api/milestone/3

[admin-1]: https://github.com/mspay/service-admin/milestone/1

[client-1]: https://github.com/mspay/service-client/milestone/1
