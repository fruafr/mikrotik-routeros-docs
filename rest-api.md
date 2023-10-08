# Mikrotik - RouterOS - Rest API - Application Programmable Interface (API) via HTTP

[Per Mikrotik's REST API documentation](https://help.mikrotik.com/docs/display/ROS/REST+API):

"The term "REST API" generally refers to an API accessed via HTTP protocol at a predefined set of resource-oriented URLs. 
Starting from RouterOS v7.1beta4, it is implemented as a JSON wrapper interface of the console API. It allows to create, read, update and delete resources and call arbitrary console commands.

To start using REST API, the ***www-ssl** or **www** (starting with RouterOS v7.9) **service** must be configured and running. When the www-ssl service (HTTPS access) is enabled, the REST service can be accessed by connecting to https://<routers_IP>/rest. When www service (HTTP access) is enabled the REST service can be accessed by connecting to http://<routers_IP>/rest."

## Authentication 

*"Authentication to the REST API is performed via HTTP Basic Auth. Provide your Username and password are the same as for the console user (by default "admin" with no password)."*

## Services
- **www-ssl** or **www** (starting with RouterOS v7.9) service must be configured and running

## Details
[Details of the Mikrotik Rest API](https://help.mikrotik.com/docs/display/ROS/REST+API): Authentication, HTTP methods, errors ...

## Note
- Not official - May be incomplete.

## Copyright
- Mikrotik, Routerboard and RouterOS are trademarks of [SIA Mikrotīkls, Latvia](https://www.mikrotik.com)
