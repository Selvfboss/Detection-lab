# 1. Elasticsearch Installation

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
