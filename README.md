🚀 IoT-Based Real-Time Sensor Monitoring and Alert System

The IoT Sensor Monitoring & Alerts Dashboard is a smart, end-to-end solution designed to continuously observe and analyze environmental conditions in real time using IoT-enabled hardware and high-speed 5G communication. The system integrates multiple sensors—including temperature–humidity, light intensity, TDS, and NPK soil sensors—with a Raspberry Pi to acquire, process, and transmit data efficiently. All sensor readings are published to an MQTT server, enabling seamless communication between edge devices and the web interface.

A responsive web dashboard visualizes live sensor data through interactive charts, logs, and telemetry panels, providing users with a clear and intuitive overview of current conditions. This architecture ensures low-latency data delivery, high reliability, and scalable deployment, highlighting the effectiveness of combining IoT hardware with lightweight messaging protocols.

Beyond visualization, the system features an intelligent alerting mechanism to support proactive monitoring. Whenever any sensor value crosses its predefined threshold, the Raspberry Pi instantly triggers an SMS notification via the Quectel 5G module, delivering precise information about the abnormal condition. This real-time alerting enables fast decision-making and timely intervention.

Overall, the project demonstrates a robust implementation of real-time data acquisition, cloud-connected visualization, high-speed wireless communication, and automated notifications—making it suitable for applications in smart agriculture, environmental monitoring, smart cities, and industrial automation.

📌 System Architecture
<img width="773" height="449" alt="Architectural Overview" src="https://github.com/user-attachments/assets/4b167d7a-fdc8-4745-917c-eb4b7bb8c362" /> *Fig: Architectural overview of the system.*
📊 Live Dashboard & Sensor Data
<img width="870" height="461" alt="Live Dashboard" src="https://github.com/user-attachments/assets/075b5e1d-7d5c-4764-99c4-83e473dd72e9" /> *Fig: Live 5G dashboard and sensor data visualization.*
🎥 Demo Video

A demonstration video of the IoT Sensor Monitoring & Alerts Dashboard is available here:
👉 https://drive.google.com/file/d/165IwX7KXSzGTNkdeyxH72lGmy2qwLjMr/view
