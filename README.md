# Tilley08_ddos
DDoS Attack Sequence

```mermaid
sequenceDiagram
    Attacker->>Botnet: Signal Vulnerable Access Point
    Botnet->>Bots: Send Requests
    Bots->>WebServer: Distribute Requests
    Botnet->>LegitimateThirdPartyServices: Phishing
    WebServer->>Firewall: Process Requests
    LegitimateThirdPartyServices->>Servers: Filter Requests
    Firewall->>Servers: Filter Requests
    Servers->>Database: Access Data
    Database->>FileSystem: Retrieve Data



    In the diagram above, the attackers discover vulnerable access points and use a control server to signal to the botnet and distributes requests foir the individual bots. One way, the bots attack is by sending a large volume of resource extensive requests that focus on applications or we pages that require database access. These attacks are hard to detect because they appear as normal traffic.

    There are many ways to try and defend against these attacks. First being proper configuration of firewalls and routers. Making sure devices are up to date with security updates can be equally as important.Educating users is probably the hardest yet most effective. You may be able to easily teach best practices, but as soon as it results in reduced usability, there will be those who are reluctant.