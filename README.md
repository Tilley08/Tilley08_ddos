# Tilley08_ddos
DDoS Attack Sequence



```mermaid
sequenceDiangram
    Attacker->>Bots:Vulnerable Access Point
    Bots->>Botnet: Send Requsts
    Botnet->>WebServer: Distribute Requests
    Botnet->>Legitimate Third Party Services: Phishing
    Webserver->>Firewall: Process Requests
    Firewall->>Servers: Filter Requests
    Servers->>Database: Access Data
    Database->>File System: Retrieve Data
    