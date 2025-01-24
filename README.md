# Tilley08_ddos
DDoS Attack Sequence

```mermaid
sequenceDiagram
    Attacker->>Bots: Vulnerable Access Point
    Bots->>Botnet: Send Requests
    Botnet->>WebServer: Distribute Requests
    Botnet->>LegitimateThirdPartyServices: Phishing
    WebServer->>Firewall: Process Requests
    Firewall->>Servers: Filter Requests
    Servers->>Database: Access Data
    Database->>FileSystem: Retrieve Data
