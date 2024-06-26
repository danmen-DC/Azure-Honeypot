# T-pot

## Objective

The Honeypot Lab project aimed to establish a controlled environment within Azure for attracting and detecting cyber attacks. The primary focus was to ingest and analyze logs using Elasticsearch/Kibana. They Honeypot gathers test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Azure firewall and virtual machine configuration and deployment.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- T-pot v24.04 within Linux distribution (ubuntu)
- Azure Cloud services: Powershell, Firewall Manager
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps

Registering basic firewall service: <br/>
<img src="https://i.imgur.com/2k3dFcD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />



DNAT port for azure goes up to 63999. Tpot needs port 64295/64297 open
