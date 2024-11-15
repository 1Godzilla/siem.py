Here’s a README file for my SIEM simulation project:

SIEM Simulation Project

A basic Security Information and Event Management (SIEM) simulation tool built in Python. This script reads system log files, parses events, and displays them in a structured format, allowing you to monitor and analyze system activities on a Kali Linux environment.

Features

	•	Reads logs from various system log files.
	•	Displays real-time log entries in the terminal.
	•	Parses log entries for easy readability.
	•	Filters logs for specific keywords (configurable).
	•	Simulates a simple SIEM environment to monitor system activities.

Requirements

	•	Python 3
	•	Required libraries (install using pip3):

pip3 install pandas watchdog



Installation

	1.	Clone this repository or download the siem_simulation.py file.

git clone https://github.com/1Godzilla/SIEM_Simulation.git
cd SIEM_Simulation


	2.	Ensure you have read access to the system log files you want to monitor. You may need to use sudo permissions to access some logs on Kali Linux.

Usage

	1.	Open the terminal and navigate to the directory where siem_simulation.py is located.
	2.	Run the script:

python3 siem_simulation.py


	3.	The script will start reading log entries from the specified log files and display them in real-time.

Configuration

The script is set to read logs from common locations (e.g., /var/log/syslog, /var/log/auth.log, etc.). You can modify the log file paths in the script as per your requirements.

Example Output

Log Entry: Nov 15 06:25:01 system CRON[417]: (root) CMD (command -v debian-sa1 /dev/null)
Log Entry: Nov 15 06:31:53 systemd[1]: Finished Cleanup of Temporary Directories.

Future Enhancements

	•	Enhanced Filtering: Add more detailed filtering options to focus on specific events.
	•	Alert System: Trigger alerts for specific events (e.g., failed login attempts).
	•	Data Visualization: Generate graphical reports using libraries like matplotlib.

License

This project is licensed under the MIT License - see the LICENSE file for details.

This README provides a clear overview of your SIEM simulation project, including its features, setup instructions, usage, and potential future improvements.