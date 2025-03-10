
<p align="center">
<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXIxYTE1eDBlNTZzc2wyYjhtYjR0bWsxY2w1bHNqNGszeTg5MWtvcSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oFyDtuYpsARhx4K0U/giphy.gif", width="300", height="300">
</p>

<h1 align="center">PHONERENSIC </h1>
<h4 align="center">ADB-Powered Toolkit for Android Forensic Analysis </h4>

### DESCRIPTION

PhoneRensic is a powerful, all-in-one Android forensic toolkit designed for security analysts, forensic investigators, and ethical hackers. It leverages ADB (Android Debug Bridge) to extract, analyze, and interact with Android devices—whether rooted or non-rooted.

With PhoneRensic, you can access critical device data, perform in-depth forensic investigations, and retrieve valuable information for incident response, digital forensics, and security analysis.

### Why Use PhoneRensic?
    🔹 Extract Hidden Data – Recover messages, call logs, and deleted files
    🔹 Analyze System Processes – Track running apps, CPU usage, and memory dumps
    🔹 Capture Network Traffic – Monitor real-time network activity and connections
    🔹 Full File System Access – Extract data from /sdcard/ or full system dumps (root required)
    🔹 Remote Device Control – Interact with the device using taps, swipes, and keyboard input
    🔹 Live Screen Mirroring – Use scrcpy to view and control the Android device remotely
    
### Key Capabilities
    ✔ Device Information Retrieval – Extract hardware details, OS version, and security patches
    ✔ File System & Memory Dumps – Dump full partitions and analyze device storage
    ✔ Wi-Fi & Network Forensics – Extract saved Wi-Fi passwords, active network connections, and packet captures
    ✔ Application Data Extraction – Retrieve chat history, saved credentials, and app-specific data
    ✔ Keylogging & Input Capture – Simulate user interactions like taps, swipes, and keyboard input
    ✔ Live Log Monitoring – Capture system logs (logcat) for real-time debugging and analysis
    ✔ Bypass Lock Screen (Root Required) – Remove PIN, pattern, or password authentication
    ✔ Forensic Data Recovery – Recover deleted messages, media files, and browser history

### Supported Devices
  * Non-Rooted Android Devices – Basic information retrieval, logs, and partial file access
  * Rooted Android Devices – Full forensic extraction, app database recovery, and deep system access

### INSTALLATION
     git clone https://github.com/0xbitx/DEDSEC_PHONERENSIC.git
     cd DEDSEC_PHONERENSIC
     sudo apt update && sudo apt install feh scrcpy adb -y && python3 -m pip install tabulate
     chmod +x dedsec_phonerensic 
     ./dedsec_phonerensic

### TESTED ON FOLLOWING
* Kali Linux 
* Parrot OS 
* Ubuntu
  


## Legal Disclaimer

This tool is intended for educational and security research purposes only. Unauthorized usage may be illegal in your jurisdiction. The author is not responsible for any misuse of this tool.

## Contributing

Pull requests are welcome! Feel free to improve the tool and submit changes.
