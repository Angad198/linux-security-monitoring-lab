# Security Log Analysis Report

## Project Overview
This project analyzes Linux authentication and system logs to identify security events, user activity, and privileged access patterns.

## Data Source
- Ubuntu authentication logs (auth_log_sample.txt)

## Key Findings

### 1. System Activity
- Monitored system login sessions
- Tracked user access events

### 2. Privileged Access (sudo)
- Identified sudo command executions
- Tracked root-level administrative actions
- Detected authentication failures during sudo usage

### 3. Security Observations
- No external brute-force attacks detected in dataset
- Internal administrative activity observed
- System logs show normal operational behavior

## Tools Used
- grep (log filtering)
- wc (count analysis)
- Linux terminal
- Ubuntu system logs

## Conclusion
The system demonstrates normal authentication behavior with controlled administrative access. Log analysis successfully identified privileged operations and system activity patterns.

## Skills Demonstrated
- Linux log analysis
- Security event detection
- System administration monitoring
- Basic SOC (Security Operations Center) analysis
