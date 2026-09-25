# SOC-SIEM-Android
SOC/SIEM Security Monitoring and Log Analysis using Android and Termux
# SOC/SIEM Security Monitoring & Log Analysis using Android/Termux

## Project Overview

This project demonstrates basic SOC/SIEM security monitoring and log analysis using an Android device with Termux.

The project includes system information collection, network information collection, simulated security-event log creation, alert filtering, severity classification, and incident documentation.

**Note:** The security events in this project are simulated for educational and controlled-lab purposes.

## Objectives

- Understand basic SOC monitoring concepts
- Collect system and network information
- Create and analyze security event logs
- Filter security alerts
- Perform basic alert triage
- Classify alerts by severity
- Document security observations and recommended actions

## Environment & Tools

- Android
- Termux
- Linux commands
- iproute2
- net-tools
- grep
- cat
- nl

## Project Activities

### 1. System Information Collection

# SOC/SIEM Security Monitoring & Log Analysis using Android/Termux

## Project Overview

This project demonstrates basic SOC/SIEM security monitoring and log analysis using an Android device with Termux.

The project includes system information collection, network information collection, simulated security-event log creation, alert filtering, severity classification, and incident documentation.

**Note:** The security events in this project are simulated for educational and controlled-lab purposes.

## Objectives

- Understand basic SOC monitoring concepts
- Collect system and network information
- Create and analyze security event logs
- Filter security alerts
- Perform basic alert triage
- Classify alerts by severity
- Document security observations and recommended actions

## Environment & Tools

- Android
- Termux
- Linux commands
- iproute2
- net-tools
- grep
- cat
- nl

## Project Activities

### 1. System Information Collection

System information was collected using:

```bash
uname -a
The current Termux user was checked using:

whoami
2. Network Information Collection
Network information was collected using:

ifconfig
The available network interfaces were reviewed during the lab.

3. Security Event Log
A simulated security event log was created and stored in:

security-events.log

The log contains INFO, WARNING and ALERT events.

4. Alert Filtering
Security alerts were filtered using:

grep "WARNING\|ALERT" security-events.log
Four simulated security alerts were identified.

5. Alert Analysis
Alert	Severity	Observation
Multiple failed login attempts	Medium	Repeated authentication failures were detected.
Failed login from 192.168.0.50	Medium	A failed login attempt was recorded from a private IP address.
Brute-force pattern detected	High	A brute-force pattern was identified in the simulated log.
Suspicious network activity detected	Medium	Suspicious network activity was recorded in the simulated log.
6. Incident Report
The detailed analysis is available in:

incident-report.txt

Project Files
security-events.log — simulated security event log

alerts.log — filtered WARNING and ALERT events

incident-report.txt — SOC incident analysis

screenshots/ — project evidence screenshots

Results
The project demonstrated:

Basic system information collection

Network information collection

Security event log analysis

Alert filtering

Severity classification

Basic SOC-style incident analysis

Security incident documentation

Conclusion
This project provided practical exposure to basic SOC monitoring, security event analysis, alert filtering, severity classification, and incident documentation using Android and Termux.

The exercise was performed using simulated security events in a controlled environment for educational purposes.

Author
Sejal Pramod Ghorpade

B.Com IT Graduate
Cybersecurity Learner


### शेवटी

README save करण्यासाठी **Commit changes** करा.

Commit message:

```text
Update project documentation
✅ हे झाल्यावर तुझा SOC/SIEM GitHub project मुख्यतः complete आहे.

Screenshots upload access परत मिळाल्यावर फक्त screenshots folder मध्ये screenshots add करायचे आहेत.


Kay kay copy karun tithe paste karayach ahe

हो 👍 GitHub च्या README.md मध्ये फक्त खालील पूर्ण content copy करून paste करायचा आहे.

काय करायचं:

GitHub → SOC-SIEM-Android

README.md उघड

✏️ Edit करा

आतला जुना content असेल तर select करून delete करा

खालील पूर्ण मजकूर copy-paste करा:

# SOC/SIEM Security Monitoring & Log Analysis using Android/Termux

## Project Overview

This project demonstrates basic SOC/SIEM security monitoring and log analysis using an Android device with Termux.

The project includes system information collection, network information collection, simulated security-event log creation, alert filtering, severity classification, and incident documentation.

**Note:** The security events in this project are simulated for educational and controlled-lab purposes.

## Objectives

- Understand basic SOC monitoring concepts
- Collect system and network information
- Create and analyze security event logs
- Filter security alerts
- Perform basic alert triage
- Classify alerts by severity
- Document security observations and recommended actions

## Environment & Tools

- Android
- Termux
- Linux commands
- iproute2
- net-tools
- grep
- cat
- nl

## Project Activities

### 1. System Information Collection

System information was collected using:

```bash
uname -a
The current Termux user was checked using:

whoami
2. Network Information Collection
Network information was collected using:

ifconfig
The available network interfaces were reviewed during the lab.

3. Security Event Log
A simulated security event log was created and stored in:

security-events.log

The log contains INFO, WARNING and ALERT events.

4. Alert Filtering
Security alerts were filtered using:

grep "WARNING\|ALERT" security-events.log
Four simulated security alerts were identified.

5. Alert Analysis
Alert	Severity	Observation
Multiple failed login attempts	Medium	Repeated authentication failures were detected.
Failed login from 192.168.0.50	Medium	A failed login attempt was recorded from a private IP address.
Brute-force pattern detected	High	A brute-force pattern was identified in the simulated log.
Suspicious network activity detected	Medium	Suspicious network activity was recorded in the simulated log.
6. Incident Report
The detailed analysis is available in:

incident-report.txt

Project Files
security-events.log — simulated security event log

alerts.log — filtered WARNING and ALERT events

incident-report.txt — SOC incident analysis

screenshots/ — project evidence screenshots

Results
The project demonstrated:

Basic system information collection

Network information collection

Security event log analysis

Alert filtering

Severity classification

Basic SOC-style incident analysis

Security incident documentation

Conclusion
This project provided practical exposure to basic SOC monitoring, security event analysis, alert filtering, severity classification, and incident documentation using Android and Termux.

The exercise was performed using simulated security events in a controlled environment for educational purposes.

Author
Sejal Pramod Ghorpade

B.Com IT Graduate
Cybersecurity Learner
