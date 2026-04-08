## Brute Force Traffic Analysis

### Observed Activity
- Repeated TCP connections from 10.10.10.10 to 10.10.10.30
- High connection frequency in short time window

### Indicators
- SYN packets without session establishment
- Consistent connection resets

### Correlation
- Matching Wazuh alerts for failed login attempts

### Conclusion
True Positive.
Network traffic confirms brute force behaviour.
