# Unauthorized Access Investigation using auditd in Linux

## 📄 Overview
This project simulates an unauthorized access incident on a Linux system using the `auditd` service to monitor and log access to a sensitive payroll file.

## 🎯 Objectives
- Monitor a sensitive file for unauthorized access attempts.
- Identify the user and method used for the access.
- Analyze Linux audit logs.
- Recommend security improvements.

## 🧪 Steps Performed
1. Created a secure payroll file and set strict permissions.
2. Added a simulated misconfiguration to grant unauthorized read access.
3. Enabled and configured `auditd` to watch the file.
4. Simulated unauthorized access using the `legal_admin` account.
5. Reviewed audit logs with `ausearch`.
6. Completed an **Access Control Worksheet**.

## 📂 Project Structure
