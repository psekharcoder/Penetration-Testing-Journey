📘 Day 03 – Wireshark Network Traffic Analysis (HTTP Packet Capture)

📌 Objective
To analyze network traffic using Wireshark and capture HTTP packets in order to understand how data is transmitted between a client and a server, including sensitive information in unencrypted communication.

🔎 Approach

Initiated packet capture using Wireshark on the active network interface
Generated network traffic by accessing a target website in the browser
Focused on HTTP-based communication to inspect readable data
Filtered and analyzed captured packets to identify relevant requests and responses

⚙️ Steps Performed

Opened Wireshark and selected the active network interface (eth0/ens33)
Started live packet capture
Accessed target website in browser (HTTP-based request)
Performed login interaction to generate HTTP traffic
Stopped capture after activity completion
Applied filters to isolate HTTP packets
Used “Follow HTTP Stream” to inspect full request-response flow
Analyzed captured data for transmitted parameters

📊 Observations

HTTP GET and POST requests were observed during browsing activity
Packet capture displayed readable data for unencrypted communication
Request parameters such as form data were visible in HTTP stream
Network traffic flow between client and server was clearly identified
Sensitive data exposure was observed in HTTP-based transmission

🧠 Key Learnings

Understanding how Wireshark captures and displays network packets
Difference between HTTP and HTTPS in terms of security
How packet inspection helps in analyzing client-server communication
Importance of encryption in protecting sensitive information
Practical exposure to network traffic analysis techniques

🎯 Outcome
Successfully captured and analyzed HTTP network traffic using Wireshark. Gained practical understanding of packet inspection and how unencrypted communication can expose sensitive data during transmission.

⚠️ This work is intended for educational purposes only.
