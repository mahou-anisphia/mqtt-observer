_From the product series "Magicodelogy"_

# MQTT Observer

> **Note:** This project is **archived**. It represents my **first exploration into network protocols beyond HTTP**. I built this tool to understand how MQTT works by observing traffic from asset tracker devices.

## 📖 About
**MQTT Observer** is a simple client tool designed to "listen" to MQTT traffic. 

Unlike standard HTTP requests where you ask for data, this tool subscribes to topics and watches for messages being broadcasted by devices (specifically asset trackers). It was created mainly for testing and debugging purposes.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Library:** `paho-mqtt`
* **Protocol:** MQTT

## ⚙️ Configuration
To use this observer, you need to configure the connection details in the `config/` directory or via environment variables (depending on your setup).

Typical configuration includes:
* **Broker Address:** The server handling the MQTT messages.
* **Port:** usually 1883 (unencrypted) or 8883 (encrypted).
* **Topic:** The specific channel to listen to.

## 🚀 Installation & Usage

### 1. Set up Virtual Environment (Optional)
```bash
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
````

### 2\. Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### 3\. Start Observing

Run the main script to start listening for messages:

```bash
python3 main.py
```

## 📄 License

This project is open for educational and archival purposes.
