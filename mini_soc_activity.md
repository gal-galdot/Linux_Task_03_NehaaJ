MINI SOC ACTIVITY

1. How would you identify resource-heavy processes?

I would use top, htop, ps, and ps aux commands to monitor CPU and memory usage. Processes consuming unusually high resources would be investigated further.

2. How would you determine whether a process is suspicious?

I would check the process name, PID, parent process, user account running it, resource usage, and network activity. Unknown or unexpected processes would be analyzed carefully.

3. What information would you collect before terminating a process?

Before terminating a process I would record:
- Process Name
- PID
- User running the process
- CPU Usage
- Memory Usage
- Command Path
- Network Connections
- System Logs

This information helps determine whether the process is legitimate and assists in incident investigation if required.
