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


```Mermaid
 info
 ```