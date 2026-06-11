# Minimum Office Network & Cyber Security Baseline for Care Providers

This section extends the gap assessment beyond privacy governance into practical cyber security controls expected for a small or medium UK care provider handling personal and special category data.

## Why this matters

Care providers process health, care, safeguarding, staff, payroll, next-of-kin and sometimes medication information. A weak office network can therefore become a data protection risk, not just an IT issue.

The baseline should be risk-based, proportionate and evidenced. It should help the organisation demonstrate that it has considered confidentiality, integrity and availability.

## Minimum baseline controls

| Area | Minimum expectation | Evidence to collect |
|---|---|---|
| Firewall / secure internet edge | Business-grade firewall or securely configured router; no unnecessary inbound services; admin access restricted; firmware updated; configuration backed up | Network diagram, firewall rule export, firmware/version evidence, change log |
| Secure Wi-Fi | Separate business and guest Wi-Fi; strong WPA2/WPA3; no shared staff/admin passwords; guest network isolated from care systems | SSID list, Wi-Fi config screenshots, VLAN/firewall policies |
| Endpoint security | Supported antivirus or EDR on laptops, desktops and servers; real-time protection enabled; automatic updates; alerts reviewed | AV/EDR coverage report, policy screenshots, alert dashboard |
| Device encryption | Laptops, removable drives and backup media encrypted where personal data may be stored | BitLocker/FileVault report, removable media controls |
| Patch and vulnerability management | Operating systems, applications, firewalls and network devices patched using risk-based SLAs | Patch dashboard, vulnerability scan report, exception register |
| Backups | Critical care, HR, finance and operational data backed up to an approved schedule with defined retention | Backup policy, backup job reports, retention settings |
| Recovery testing | Restores tested regularly, not just backup jobs marked as successful | Restore test log, screenshots, RTO/RPO notes, lessons learned |
| Ransomware resilience | Backups protected from compromise using immutable, offline or separately secured controls | Immutable backup setting, offline copy record, separate admin account evidence |
| Secure transmission | Backup traffic and data transfers encrypted in transit using TLS, VPN or equivalent secure channels | TLS/VPN configuration, supplier confirmation, backup encryption settings |
| Logging and monitoring | Firewall, endpoint and critical system logs retained and reviewed proportionately | Log settings, alert reports, incident tickets |

## Suggested assessment questions

1. Can management show a current network diagram?
2. Is the firewall/router managed, patched and documented?
3. Are care systems separated from guest Wi-Fi?
4. Is antivirus/EDR coverage above 95% of known assets?
5. Are all laptops encrypted?
6. Are backups running successfully according to policy?
7. Has a restore test been completed in the last quarter?
8. Are backup transfers encrypted?
9. Are backup admin accounts separate from normal user accounts?
10. Are critical vulnerabilities tracked to closure?

## Recruiter value

This section shows that the project is not only a policy exercise. It connects GRC, vulnerability management, cyber hygiene, supplier assurance, evidence collection and operational resilience.
