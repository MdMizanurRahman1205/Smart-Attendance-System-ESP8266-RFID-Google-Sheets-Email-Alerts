# 𝗦𝗺𝗮𝗿𝘁-𝗔𝘁𝘁𝗲𝗻𝗱𝗮𝗻𝗰𝗲-𝗦𝘆𝘀𝘁𝗲𝗺-𝗘𝗦𝗣𝟴𝟮𝟲𝟲-𝗥𝗙𝗜𝗗-𝗚𝗼𝗼𝗴𝗹𝗲-𝗦𝗵𝗲𝗲𝘁𝘀-𝗘𝗺𝗮𝗶𝗹-𝗔𝗹𝗲𝗿𝘁𝘀

I just completed a smart RFID attendance system powered by ESP8266 (NodeMCU), integrated with Google Sheets for data storage and automated email confirmation — all without any third-party servers!

📚 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄:
This system offers a contactless, real-time attendance solution that reads RFID cards, matches UID to user data, logs it in Google Sheets, and sends an email confirmation to the student or attendee instantly.

🔍 𝗛𝗼𝘄 𝗜𝘁 𝗪𝗼𝗿𝗸𝘀:
RFID card is scanned using MFRC522.
ESP8266 reads the UID and maps it to stored user data (Name, Roll No, Department, Email).
Data is sent via HTTPS POST to a Google Apps Script endpoint.
The script logs attendance in Google Sheets and triggers an automated email confirmation to the registered email ID.
A buzzer feedback confirms successful scan.

🛠️ 𝗧𝗲𝗰𝗵 𝗦𝘁𝗮𝗰𝗸 𝗨𝘀𝗲𝗱:
ESP8266 (NodeMCU)
MFRC522 RFID Module
Google Apps Script (for Sheets + Email)
Arduino IDE (for coding)
WiFiClientSecure for secure HTTPS communication

💡 𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀:
✅ Cloud-based attendance log (Google Sheets)
✅ Auto email confirmation after every scan
✅ Real-time Wi-Fi communication
✅ Visual feedback via buzzer
✅ Fully serverless and scalable
✅ Ideal for classrooms, events, labs, and office check-ins

📬 𝗕𝗼𝗻𝘂𝘀: Attendees receive an email like
"Hi [Name], your attendance has been successfully recorded on [Date, Time]." — great for transparency and record-keeping.

🎯 𝗨𝘀𝗲 𝗖𝗮𝘀𝗲𝘀:
Educational Institutions
Tech Fests and Seminars
Company Check-ins
Libraries or Lab Access Control

𝐃𝐞𝐬𝐢𝐠𝐧𝐞𝐝 𝐚𝐧𝐝 𝐝𝐞𝐛𝐮𝐠𝐠𝐢𝐧𝐠 𝐁𝐲 𝐌𝐃 𝐌𝐈𝐙𝐀𝐍𝐔𝐑 𝐑𝐀𝐇𝐌𝐀𝐍
