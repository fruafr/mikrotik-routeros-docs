# Mikrotik - RouterOS - Application Programmable Interface (API)

[Per Mikrotik's API documentation](https://help.mikrotik.com/docs/display/ROS/API):

*Application Programmable Interface (API) allows users to create custom software solutions to communicate with RouterOS to gather information, adjust the configuration, and manage the router. API closely follows syntax from the command-line interface (CLI). It can be used to create translated or custom configuration tools to aid ease of use running and managing routers with RouterOS.*

The API is suitable for lower level integration with other software or programming languages (e.g. Python).

## Services 

- **api** service must be enabled before trying to establish the API connection. By default, **API uses TCP:8728** and **TCP:8729 (secure)**. 

- **api-ssl** service is capable to work in two modes - with and without a certificate. In the case no certificate is used in /ip service settings then anonymous Diffie-Hellman cipher have to be used to establish connection. If certificate is in use, TLS session can be established.*

## Details
[Details of the Mikrotik RouterOS API](https://help.mikrotik.com/docs/display/ROS/API)

## Note
- Not official - May be incomplete.

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)