# Security Monitoring Commands Research

## netstat

Purpose:
Displays network connections, routing tables, interface statistics, and listening ports.

Example Output:
tcp 0 0 0.0.0.0:22 0.0.0.0:* LISTEN

Security Use Case:
Helps identify suspicious open ports and unauthorized network connections.

---

## ss

Purpose:
Displays socket statistics and active network connections.

Example Output:
tcp LISTEN 0 128 *:22 *:*

Security Use Case:
Used to quickly identify active services and network activity.

---

## who

Purpose:
Shows currently logged-in users.

Example Output:
student tty1 2025-06-14 09:15

Security Use Case:
Helps detect unauthorized user sessions.

---

## w

Purpose:
Shows logged-in users and their activities.

Example Output:
USER TTY FROM LOGIN@ IDLE JCPU PCPU WHAT

Security Use Case:
Useful for monitoring active users and commands being executed.

---

## last

Purpose:
Displays login history from the system log.

Example Output:
student pts/0 192.168.1.10 Sun Jun 14

Security Use Case:
Allows administrators to investigate previous login attempts and suspicious access.
