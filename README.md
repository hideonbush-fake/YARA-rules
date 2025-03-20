# YARA-rules

## Objective
This project focuses on leveraging YARA to develop and refine detection rules for identifying malware threats and related artifacts. By crafting precise YARA rules, the goal is to enhance threat visibility and improve detection accuracy.

### Skills Learned
- Identify malware patterns and indicators of compromise (IOCs) for improved security monitoring
- Create precise Yara rules to detect malware while minimizing false positives

## RULE 1
Create a YARA detection rule for any executable files that match this base domain of FreeYoutubeDownloader.exe.meow binary. 

![Screenshot 2025-03-20 091120](https://github.com/user-attachments/assets/cbfd7eb6-53cf-4fb0-a930-7cf1e1275762)

![Screenshot 2025-03-20 091131](https://github.com/user-attachments/assets/99fe3737-d539-43b2-9bad-5a217949aa84)

![Screenshot 2025-03-20 092138](https://github.com/user-attachments/assets/ae6d818e-7225-4c1b-9d5c-1423b9a07439)

## RULE 2
Create a YARA rule only to detect the registry key inside FreeYoutubeDownloader.exe.meow binary. 

![Screenshot 2025-03-20 092625](https://github.com/user-attachments/assets/7976c57b-8781-4776-b2ef-cd1f0d779979)

- grep using \\ because in YARA a single backslash is an escape character
- ensure that YARA correctly recognizes \ as a literal character rather than an escape sequence

![Screenshot 2025-03-20 092632](https://github.com/user-attachments/assets/5389ebaf-2f05-4a2f-9ddc-d63f54f7d2eb)

![Screenshot 2025-03-20 092936](https://github.com/user-attachments/assets/ce4c8c47-6139-4f84-aa24-d241f293a1ea)

## RULE 3
Create a YARA rule to detect any GIF89a files under 50 KB in size. 

![2025-03-20 09_44_41-List of file signatures - Wikipedia](https://github.com/user-attachments/assets/54706556-315a-444e-b238-9fdb7af234e6)

- Discovered the hex signatures of GIF file extensions to incorporate them into my YARA rules.

![Screenshot 2025-03-20 093345](https://github.com/user-attachments/assets/cb525d6c-f1ef-425d-b473-2f7cb0af9488)





