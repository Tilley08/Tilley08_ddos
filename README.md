# Tilley08_ddos
DDoS Attack Sequence


```mermaid
sequenceDiagram
    Bots->BotNet: Send Requests
    BotNet->WebServer: Distribute Requests
    WebServer->Firewall: Process Requests
    Firewall->Servers: Filter Requests
    Servers->Database: Access Data
    Database->FileSystem: Retrieve Data
    FileSystem->Employee: Store Data

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
