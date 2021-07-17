# DynamicDNS

Features
--------
- Auto Dynamic IP address updater for google domains
- Creates a service for the updating the DNS entry

Platforms
------------
- Python code works on Windows, MacOS and Linux
- Service creation is supported only on Linux

Requirements
------------
- python3

 
How to use?
------------
1. Clone the repository
2. Install python3
3. Open the file google-ddns-update.py
   in the following lines
   ```
   username = ""
   password = ""
   hostname = ""
   ```
   enter your details from google domains
 4. Save changes
 5. run the following command to install as startup service
    ```
    sh install-service
    ```
 
 Starting service
 ----------------
 Type the following command on the terminal
 ```
 sudo systemctl start google-ddns-updater.service
 ```
 
 Stopping service
 ----------------
 Type the following command on the terminal
 ```
 sudo systemctl stop google-ddns-updater.service
 ```

