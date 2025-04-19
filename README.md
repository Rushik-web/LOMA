# 🛡️ LOMA - Log Monitoring and Analysis Tool

**LOMA** (Log Monitoring Application) is a cross-platform, GUI-based log analyzer built with Python and Tkinter. It enables both real-time log monitoring and EVTX file parsing, making it an essential tool for SOC analysts, incident responders, and Windows/Linux system administrators.

---

## 🚀 Features

- 📂 **EVTX File Parsing**: Load and parse Windows `.evtx` event log files.
- 🔍 **Real-Time Monitoring**:
  - On **Windows**: Monitors live system logs using `win32evtlog`.
  - On **Linux**: Reads logs from `/var/log/syslog` or `/var/log/messages`.
- 🎛️ **Severity Filtering**: Dynamically filter logs by severity like:
  - Critical
  - Error
  - Warning
  - Information
  - Audit Success / Failure
- 📑 **Report Generation**: Export filtered logs to `.evtx` or `.csv` format.
- 🧠 **Threaded UI**: Responsive UI even during file parsing or live log reading.
- 🌗 **Dark-Themed UI**: A clean, customizable UI with real-time output area.

---

## 📸 Image


![UI](/LOMA_Image.jpeg)


---

## 🛠️ Requirements

- Python 3.7+
- Libraries:
  ```bash
  pip install evtx
  pip install pywin32

## 📦 How to Run
Clone the repo:
git clone https://github.com/Rushik-web/LOMA.git
cd LOMA

## Run the application:
python "LOMA FINAL.PY"

## Usage:
Click Load & Parse Logs to analyze .evtx files.
Click Start Live Monitoring to begin real-time log capture.
Use the filter panel to filter logs by severity.
Use Generate Report to save filtered logs.


