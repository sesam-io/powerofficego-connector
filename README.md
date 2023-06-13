# PowerOffice Go
A Sesam connector for PowerOffice Go

# How to test

The following environment varibles need to be configured:

`base_url` see https://api.poweroffice.net/Web/docs/index.html#Rest/Urls.md

`application_key` and `client_key` (`client_key` is mapped to system secret `api_key` due to how our `api_key` auth type work) see https://api.poweroffice.net/Web/docs/index.html#Common/Registration.md


When inserting an invoice use `status` `0` (draft) or `1` (confirmed). The PowerOffice Go API won't accept any other invoice status.
