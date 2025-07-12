# AstraNet

AstraNet is a lightweight secure communications toolkit designed for distributed logistics networks operating in critical environments.
It provides a Python API for encrypted messaging, dynamic routing, and automated failover between nodes.

---

## ✨ Features
- AES-256 encryption for all messages
- Resilient multi-node routing with automatic failover
- REST API for integration with existing logistics platforms
- Lightweight footprint for edge devices

---

## 📦 Installation
```bash
git clone https://github.com/astralink-sys/AstraNet.git
cd AstraNet
pip install -r requirements.txt

---
#Usage Example:
from astra import AstraNet

client = AstraNet(node_id="node-01", config="config/example_config.yaml")
client.send_message("node-02", "Resupply convoy confirmed.")
----
#Example Config:
nodes:
  - https://node01.example.com
  - https://node02.example.com
encryption: AES256
retry_interval: 30  # seconds
-------------------------------






⚠️ Disclaimer
This project is intended for internal use within AstraLink Systems. Unauthorized access or redistribution is prohibited.
