# Tilley08_ddos
DDoS Attack Sequence


```mermaid
Graph TD;
    Bots -->|Send Requests| BotNet;
    BotNet -->|Distribute Requests| WebServer;
    WebServer -->|Process Requests| Firewall;
    Firewall -->|Filter Requests| Servers;
    Servers -->|Access Data| Database;
    Database -->|Retrieve Data| FileSystem;
    FileSystem -->|Store Data| Employee;
```