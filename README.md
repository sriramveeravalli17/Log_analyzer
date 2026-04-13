# Log File Analyzer

A Python-based security tool for analyzing system log files to detect threats and suspicious activity — built as part of my SOC/VAPT learning journey.

## About This Project

I built this tool to understand how Security Operations Center (SOC) analysts and penetration testers analyze log evidence. It replicates core post-exploitation analysis workflows used in professional VAPT engagements.

## Features

- Detects brute-force login attempts
- Flags suspicious IP addresses
- Identifies privilege escalation events
- Generates structured summary reports
- Visualizes attack patterns using matplotlib

## How to Run

```bash
pip install -r requirements.txt
python log_analyzer.py
```

## Sample Output

The tool parses auth logs and flags:
- IPs exceeding failed login thresholds
- Unusual sudo/su usage
- Invalid user enumeration attempts

## Skills Demonstrated

- Python scripting
- File I/O and string parsing
- Anomaly detection logic
- Log evidence analysis
- Security reporting

## Author

Sriram Veeravalli  
[GitHub](https://github.com/sriramveeravalli17)