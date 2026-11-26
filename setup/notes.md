# 1. Home Lab Infrastructure

## Hypervisor
Hypervisor: VMware Worksatation

Purpose: To create and manage the virtual machines used in the lab.

## Virtual Machines
Ubuntu Server - Purpose is to host the ELK stack

Windows VM - Purpose is to generate endpoint security telemetry

## VM screenshots
<img width="1202" height="696" alt="WinVM" src="https://github.com/user-attachments/assets/ebc3f1ff-f5bd-4bed-989a-f1fcd0afa3f1" />

<img width="1271" height="875" alt="ububtuVm" src="https://github.com/user-attachments/assets/1c7cd079-47b6-4a01-9662-a8c164bc71ba" />




# 2. Elasticsearch Installation

### Environment
- Operating System: Ubuntu Server
- Component: Elasticsearch

### Verification

After installation, I verified that Elasticsearch was running using: **sudo systemctl status elasticsearch**

The service returned an active (running) status, confirming that Elasticsearch was running successfully.

I then tested its API endpoint using:  **curl -k -u elastic https://localhost:9200** 

Elasticsearch returned a JSON response containing cluster information, node details and version information.

### Evidence
<img width="736" height="335" alt="Elastic-search response api" src="https://github.com/user-attachments/assets/1f80e894-14c8-46df-a53a-d0f18c6de85e" />
<img width="1322" height="387" alt="Elastic search installation" src="https://github.com/user-attachments/assets/7e93cf2d-fa9c-4841-b974-44244a26b815" />
