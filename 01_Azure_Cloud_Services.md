# Azure Compute Resources:


- Azure Virtual Mechine          
- Azure Mechine Scale Sets     
- Azure Kuberbetes Services
- Azure App Services
- Azure Functions

# Ways to Connect to VM in Azure:


| Method      | Interactive | Secure  | Public IP Needed | Cost   |
| ----------- | ----------- | ------- | ---------------- | ------ |
| Bastion     | ✅           | 🔥 High | ❌                | 💰     |
| Run Command | ❌           | 🔥 High | ❌                | Free   |
| SSH Public  | ✅           | ❌       | ✅                | Free   |
| RDP Public  | ✅           | ❌       | ✅                | Free   |
| VPN         | ✅           | 🔥 High | ❌                | Medium |
| Jumpbox     | ✅           | Medium  | ✅ (jump only)    | Low    |
