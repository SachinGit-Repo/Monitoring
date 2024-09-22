# Monitoring Free RAM Space
In this project, I developed a simple yet effective script called ram_status.sh to monitor available RAM in a Linux environment. The script checks the free memory in real-time and alerts the user when RAM space drops below a specified threshold.

The script works by fetching the current available memory using the free command and compares it against a set alert value (in this case, 1000 MB). If the available memory is below the threshold, it outputs a warning indicating low memory. Otherwise, it informs the user that the RAM usage is within acceptable limits.

This tool can be integrated into routine system checks, providing quick insight into memory health and helping to prevent performance degradation due to low memory.

# Key Features:

Monitors free memory in real-time.
Alerts when free memory drops below a pre-defined threshold.
Can be automated or scheduled for regular checks.
