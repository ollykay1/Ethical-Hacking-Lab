## Comparing Passive vs Active Reconnaissance

| **Aspect** | **Passive Reconnaissance** | **Active Reconnaissance** |
|-------------|----------------------------|---------------------------|
| **Tool Examples** | `whois`, `theHarvester`, `nslookup` | `nmap`, `ping`, `netdiscover`, `traceroute` |
| **Risk Level** | Low | High |
| **Detection Possibility** | Minimal | High |

### Summary

Passive reconnaissance gathers information without directly engaging the target, using publicly available sources such as domain records, DNS data, and search engines. It’s ideal for early information gathering when stealth is important.  

Active reconnaissance directly interacts with the target using tools like `nmap`, `ping`, and `netdiscover` to discover open ports, live hosts, and services. It provides more detailed insights but has a higher risk of detection and should only be done with authorization.
