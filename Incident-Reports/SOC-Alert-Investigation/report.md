# 🔍 SOC Alert Investigation Report

## 📌 Scenario

Multiple failed login attempts detected from a single IP address in a simulated SOC environment.

## 🛠 Tools Used

* Splunk (SIEM)
* Log Analysis

## 🔎 Investigation Steps

1. Searched authentication logs using Splunk queries
2. Identified repeated failed login attempts
3. Correlated timestamps and source IP address
4. Checked for successful login attempts after failures

## 🚨 Findings

* 50+ failed login attempts from IP: 192.168.1.10
* Pattern indicates possible brute-force attack
* No successful login detected

## ✅ Conclusion

The activity is consistent with a brute-force attack attempt. Recommended actions include blocking the IP address and enabling account lockout policies.

## 📚 Skills Demonstrated

* Log Analysis
* Threat Detection
* Incident Response
* SIEM Monitoring
