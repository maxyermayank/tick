# Configuration

[Back To README](README.md)

## **To enable Ping you iputils-ping package needs to be added to Telegraf**
```
[[inputs.ping]]
  interval = "60s"
  urls = ["amazon.com", "google.com"]
  count = 4
  ping_interval = 1.0
  timeout = 2.0
```