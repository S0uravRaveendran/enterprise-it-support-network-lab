\# Enterprise IT Support \& Network Troubleshooting Lab



\## Project Overview



This project demonstrates practical IT support and networking skills through a simulated enterprise network built in Cisco Packet Tracer, alongside Windows network troubleshooting exercises.



The lab focuses on network segmentation, IP configuration, connectivity testing, fault identification, corrective actions, and technical documentation.



\## Objectives



\* Build a small enterprise network with separate departmental VLANs.

\* Configure inter-VLAN routing using router subinterfaces.

\* Test network connectivity and identify configuration errors.

\* Practice Windows network diagnostic commands.

\* Document troubleshooting procedures and incident resolution.



\## Lab Environment



| Component               | Details                             |

| ----------------------- | ----------------------------------- |

| Network simulator       | Cisco Packet Tracer                 |

| Network devices         | 1 router, 1 switch, 3 PCs           |

| Departments             | IT, HR, Finance                     |

| Client operating system | Windows 11                          |

| Diagnostic tools        | Command Prompt networking utilities |



\## Project Screenshots



\### 1. Network Topology



!\[Network Topology](Screenshots/network\_topology.png)



\### 2. VLAN Configuration



!\[VLAN Configuration](Screenshots/Vlan\_configuration.png)



\### 3. Router Interfaces



!\[Router Interfaces](Screenshots/router\_interfaces.png)



\### 4. Successful Connectivity Test



!\[Successful Ping](Screenshots/successful\_ping.png)



\### 5. Simulated Network Failure



!\[Network Failure](Screenshots/network\_failure.png)



\### 6. Troubleshooting Resolution



!\[Troubleshooting Resolution](Screenshots/troubleshooting\_resolution.png)



\### 7. Windows IP Configuration



!\[Windows IP Configuration](Screenshots/windows\_ipconfig.png)



\### 8. Windows Connectivity Tests



!\[Windows Connectivity Tests](Screenshots/windows\_connectivity\_tests.png)



\### 9. DNS Lookup — Google



!\[Google DNS Lookup](Screenshots/dns\_lookup.png)



\### 10. DNS Lookup — Microsoft



!\[Microsoft DNS Lookup](Screenshots/dns\_lookup\_microsoft.png)



\### 11. Traceroute — Google



!\[Google Traceroute](Screenshots/traceroute\_google.png)



\## Network Design



The simulated network contains three departmental VLANs.



| Department | VLAN ID | Network         | PC IP Address | Default Gateway |

| ---------- | ------: | --------------- | ------------- | --------------- |

| IT         |      10 | 192.168.10.0/24 | 192.168.10.10 | 192.168.10.1    |

| HR         |      20 | 192.168.20.0/24 | 192.168.20.10 | 192.168.20.1    |

| Finance    |      30 | 192.168.30.0/24 | 192.168.30.10 | 192.168.30.1    |



\### Network Configuration



\* Created VLANs for departmental network segmentation.

\* Assigned switch ports to the appropriate VLANs.

\* Configured an 802.1Q trunk between the switch and router.

\* Configured router subinterfaces for inter-VLAN routing.

\* Configured IP addresses, subnet masks, and default gateways on client PCs.

\* Saved device configurations.



\## Troubleshooting Scenario



\### Issue: Incorrect Default Gateway



\*\*Problem:\*\* A simulated connectivity failure was introduced by configuring the HR PC with an incorrect default gateway.



\*\*Investigation:\*\* Connectivity tests were performed to identify the configuration issue.



\*\*Corrective action:\*\* The incorrect gateway was replaced with `192.168.20.1`.



\*\*Verification:\*\* Connectivity was tested again after the correction.



This exercise demonstrates a structured troubleshooting approach: identify the issue, investigate the configuration, apply a targeted fix, and verify the result.



\## Windows Network Troubleshooting



The following Windows Command Prompt utilities were used during the lab:



| Command                  | Purpose                                              |

| ------------------------ | ---------------------------------------------------- |

| `ipconfig /all`          | Inspect IP configuration, gateways, and DNS settings |

| `ping 127.0.0.1`         | Test the local TCP/IP stack                          |

| `ping 8.8.8.8`           | Test connectivity to an external IP address          |

| `ping google.com`        | Test connectivity using a hostname                   |

| `nslookup google.com`    | Check DNS name resolution                            |

| `nslookup microsoft.com` | Check DNS name resolution for another hostname       |

| `tracert google.com`     | Examine the network path to a destination            |



\## Documentation



The `documentation/` directory contains:



\* `incident\_reports.txt` — records of troubleshooting exercises and their outcomes.

\* `network\_inventory.txt` — network device and addressing information.

\* `troubleshooting\_checklist.txt` — a repeatable troubleshooting procedure.



The `screenshots/` directory contains visual evidence of the topology, configurations, connectivity tests, and troubleshooting process.



\## Skills Demonstrated



\* Basic network configuration and troubleshooting

\* VLAN creation and network segmentation

\* Inter-VLAN routing

\* IP addressing and subnetting fundamentals

\* Default gateway troubleshooting

\* Windows network diagnostics

\* DNS resolution testing

\* Traceroute analysis

\* Incident documentation

\* Structured problem-solving



\## Project Scope



This is a self-directed learning lab created for practical skill development and portfolio demonstration. It uses a simulated network rather than a production enterprise environment.



\## Author



\*\*Sourav Raveendran\*\*



Aspiring IT Support / Desktop Support / Network Support Professional



