# Welcome to CZERTAINLY!

![CZERTAINLY-logo](czertainly-logo/czertainly_color_H.svg)

CZERTAINLY is a platform for effective and efficient certificate lifecycle management for companies of any size and individuals. One of its goals is to provide an easy and affordable way to secure digital communication and support information security in more and more connected world.

CZERTAINLY is released as a commercial open source project under the [MIT License](LICENSE.md).
Additional features and services are available under subscription plans. If you are interested in subscription, please contact us through [CZERTAINLY Official Web](https://www.czertainly.com) or use the [CZERTAINLY Offical email address](mailto:getinfo@czertainly.com) email address.

CZERTAINLY is designed and developed by a team of PKI and information security enthusiasts with practical point of view on the certificate management in hybrid environments. PKI is the backbone of security in our daily communication and its security and easy management should be available to everyone.

## CZERTAINLY features

The CZERTAINLY platform aims to provide easy, secure, and extensible features for certificate management. Among the features are:
- certificate management (issuing, revocation, renewal) through RA profile
- extensible connectors to support many technologies and implementations of certification authorities, credentials, discovery engines, and more
- certificate searching in various sources
- consistent inventory of certificates (owners, groups, entities, profiles, and more)
- dashboard for monitoring and reporting

## About the platform

The platform is split into several components:
- interfaces (UIs, REST API, etc.)
- authentication and authorization
- core services provided by the platform (discovery, inventory, connectors, authorities, etc.)
- grouping and entity automation
- data storage
- connectors and functional groups and types (discovery provider, ca connector, credential provider, etc.)

Components in the platform acts as micro-services and the main approach is to keep each service as a simple container. 

## Repositories

| Repository                                                                                                    | Description                                                                                                                                                                                         |
|---------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [CZERTAINLY-Interfaces](https://github.com/3KeyCompany/CZERTAINLY-Interfaces)                                 | Interfaces to build custom connectors and extend the platform. Each interface is build as a REST API and you can use any technology for building your own extension you like                        |
| [CZERTAINLY-Core](https://github.com/3KeyCompany/CZERTAINLY-Core)                                             | Core services of the platform. This is the brain of the platform taking care about all operation with certificates and managing the connection between different types of connector implementations |
| [CZERTAINLY-Documentation](https://github.com/3KeyCompany/CZERTAINLY-Documentation)                           | Documentation of the platform containing also information for contributors and developers                                                                                                           |

### Providers and Connectors

| Repository                                                                                                    | Description                                                                           |
|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| [CZERTAINLY-Common-Credential-Provider](https://github.com/3KeyCompany/CZERTAINLY-Common-Credential-Provider) | Common credential provider that allows to work with basic credentials in the platform |

## Contribution

Anyone can contribute to CZERTAINLY and we would be happy to support you in that. See [Contribution Guide](CONTRIBUTING.md) for more information.

## License

The CZERTAINLY platform is released under the [MIT License](LICENSE.md). Some connectors and user interfaces are released under their own licenses or subscriptions. Consult with us for more information.

## About the subscription option

Our goal is to support everyone with affordable certificate lifecycle management and to manage certificates and cryptographic keys effectively and securely. We are not a certification authority, and we do not issue certificates. However, like all of us, we need to make some revenue in order to develop further and support our work and lives.

Therefore, we offer subscription based features for our users. With an active subscription you can use the platform with additional functions and connectors that are developed and maintained by us.

This helps us to keep the platform free and open source and provide a better service for everyone.

We are happy to help you out in building other connectors and provide it as open source in the future.
