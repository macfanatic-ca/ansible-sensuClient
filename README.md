# Sensu Client

## Function
Installs and configures the Sensu client.

## Vault
```
---
sensuClient_RabbitMQ_USER: username
sensuClient_RabbitMQ_PASS: password
sensuClient_RabbitMQ_URL: rabbitmq.example.com
sensuClient_RabbitMQ_PORT: 5671
sensuClient_RabbitMQ_VHOST: /sensu
sensuClient_SSL_Cert: path/to/cert.pem
sensuClient_SSL_Key: path/to/key.pem
```

## Tested Environment(s)
RHEL 7, CentOS 7, & macOS 10.12

## Dependancies
Installation on macOS 10.12 depends on Homebrew being installed.

## Changelog

**v1.0 (2016-11-01)**
* Original Release
