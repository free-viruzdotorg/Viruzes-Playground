# Viruzes-Playground
This is an information security based playground for all and is encouraged to use, fork, and modify at your own free will to learn, improve and get as much experience as you please all for free

This is my personal project to give back to the community for free and learn cybersecurity in a safe and fun aspect of all use cases

This project is aimed for doing the following in the environment all within one web user interface. This can either be deployed in an offline infrastructure with all internal routing, having a primary node then deploying a sensor as a replica for aggregation of logs, events and ability to take action from a remote and secure environment:

**Networking**

- Network traffic analysis with parsed fields and is customizable by the user
- Network topology and asset management (Physically and logically); fully interactive in a web user interface
- Ability to use Mangle to manipulate packet routing to be pushed from the elastic agent to the endpoint to allow only specific routing on the endpoint to be used.

System logs, event logs, Compliant checks

- Log analysis with visuals and ease for querying of data
- Ability to aggregate and parse logs from linux/unix based distributions, Windows Operating systems
- Saving filters and multiple dashboards for the user to use on different use cases easily along with allowing exporting of data either sent via email, pdf, csv and even an output of the data from the Dashboard when query'd or guest access to - the dashboard from within a secured environment.
- Verification of backups are being verified on the systems, taking action

Geographical blocking, Intrusion Detection and Prevention System:

- Allowing the user to either block Geographical regions and alert when connected remotely from them
- Allowing either Suricata or Snort to be used with IDS or IPS core functions that is user customizable with a base set of Emerging Threat Open rulesets

Security Orchestration and Automation Response (SOAR) and Endpoint Detection and Response (EDR) Solutions:

- Ability to automate, configure and manage tasks within the environment using Shuffle SOAR automation
- Use of Wazuh as an EDR with ease of customization for compliance checks, configuring and managing rulesets with alerts sent to a dashboard, email chain or specific end user
- Ability to remediate and take action within the dashboard in the event of a compromised endpoint(s), subnet(s) or entire infrastructure

Sandbox with snapshots being done in a containerized environment

- This will be similar to how Cuckoo sandbox will operate having the ability to do Dynamic and Static analysis of malware in the environment that is containerized and is pushed from the environment pulling from well known detection and verification APIs (Popular one known as VirusTotal) to have the ability to reach out to the internet or not (depends on user) then exports a report with all the agents tools to the system. This will also utilize a tool called "INetSim" to simulate network traffic within the container to make it realistic and allows the user to directly connect to the system and interact with themselves and save the data to a system, server or even locally for analysis later.
- This will be utilizing the XenAPI for management and be used as a nested virtualization software (TBD)

Other core based tools:

- CyberChef
- MITRE Attack framework table
- Sigma Playbooks
- Influx Database (InfluxDB)
- OSQuery Manager
- Saltstack
- Docker
