## SOC Investigation Summary

### Alert Source
Wazuh – authentication anomaly

### Investigation Steps
- Review failed login events
- Confirm source IP and target host
- Validate behaviour using packet capture

### Verdict
True Positive – simulated brute force attack.

### Recommended Action
- Verify no successful authentication
- Consider account lockout policy
- Monitor source IP
