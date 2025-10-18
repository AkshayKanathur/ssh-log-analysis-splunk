# SSH log analysis using Splunk
This project simulates analysing ssh log to find brute-force attempts, successful login, multiple failed login attempts, etc...

## Tools Used
- Splunk enterprise
- Kali linux

## Steps Performed
- Imported SSH log file to splunk
- Analysed fields
- Used SPL (Search Processing Language) to perform tasks like
  - List the top 10 endpoints with failed SSH login attempts
  - Find the number of total SSH connections
  - Count all event types (successful, failed, no-auth, multiple-failed) seen in the logs
  - Create a table which contains origin host and how many times it attempted to connect to ssh, it helps to detect brute-force attempts, aka Multiple failed login attempts.

## Screenshots
<img width="1920" height="1020" alt="Screenshot 2025-10-18 130642" src="https://github.com/user-attachments/assets/3410cf20-06d6-4c1c-a136-7976628aac16" />
<img width="1920" height="1020" alt="Screenshot 2025-10-18 130726" src="https://github.com/user-attachments/assets/b21776a6-7c62-44a5-a106-9347fcb36114" />
<img width="1920" height="1020" alt="Screenshot 2025-10-18 130821" src="https://github.com/user-attachments/assets/2964d792-3751-4261-8438-dba1a225c4e5" />
<img width="1920" height="1020" alt="Screenshot 2025-10-18 131123" src="https://github.com/user-attachments/assets/2ed80d16-d614-42a2-a126-67751400a792" />
<img width="1920" height="1020" alt="Screenshot 2025-10-18 131844" src="https://github.com/user-attachments/assets/309629d3-852f-4d1f-9145-0c0747b89d68" />


## Outcome
Successfully analysed SSH log file using SPL.

## Note
This was a self-simulated lab exercise for learning and practicing.
