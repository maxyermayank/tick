# Configuration

[Back To README](README.md)

```
[[inputs.activemq]]
  ## Required ActiveMQ Endpoint
  server = "activemq"

  ## Required ActiveMQ port
  port = 8161
  
  ## Credentials for basic HTTP authentication
  username = ""
  password = ""

  ## Required ActiveMQ webadmin root path
  webadmin = "admin"

  ## Maximum time to receive response.
  # response_timeout = "5s"
  
  ## Optional TLS Config
  # tls_ca = "/etc/telegraf/ca.pem"
  # tls_cert = "/etc/telegraf/cert.pem"
  # tls_key = "/etc/telegraf/key.pem"
  ## Use TLS but skip chain & host verification
```