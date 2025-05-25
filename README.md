# SSL/TLS Security Assessment - sifaris.walingmun.gov.np

This repository contains the security assessment report of the SSL/TLS configuration for the domain `sifaris.walingmun.gov.np` conducted on May 25, 2025. The assessment was done using SSL Labs and supplemented with CLI scanning tools for a comprehensive overview.

---

## Contents

- `ssl_tls_analysis_sifaris_walingmun_gov_np.md`: Detailed SSL Labs-based report and findings.
- `sslscan_output.txt`: Output from a command-line SSL scanner.
- `nmap_ssl_scan.txt`: Output from an nmap SSL/TLS scan.

---

## Summary

The target server failed to respond properly to SSL Labs scans due to connection issues and an invalid certificate version. Recommendations include updating the SSL certificate to X.509 v3, enabling modern TLS protocols, and ensuring network availability on port 443.

---

## Tools Used

- [SSL Labs](https://www.ssllabs.com/ssltest/)
- `sslscan` (command-line tool)
- `nmap` with `--script ssl-enum-ciphers`

---

## Author

Subash Gurung  
Cybersecurity Analyst  
May 25, 2025
