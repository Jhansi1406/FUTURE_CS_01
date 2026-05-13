# FUTURE_CS_01
Future Interns Cyber Security Task 1
# Future Interns - Task 1

## Vulnerability Assessment Report

### Tool Used
- Nmap

### Target
scanme.nmap.org

### Scan Type
Intense Scan

## Findings

| Port | Service | Risk |
|------|---------|------|
| 22 | SSH | Low |
| 80 | HTTP | Medium |
| 9929 | Nping Echo | Low |
| 31337 | tcpwrapped | Low |

## Recommendations

- Use secure authentication
- Enforce HTTPS
- Restrict unnecessary services
- Monitor exposed ports

## Conclusion

The target system exposes four services. HTTP service presents medium risk due to potential unencrypted communication, while other services require access control and monitoring.
