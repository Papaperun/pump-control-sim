# pump-control-sim
Simulates hysteresis-based pump control logic with real-time plotting for SCADA and automation training modules.
pump-auto-sim

A standalone Python simulation to model automatic pump behavior based on tank levels using float switches or level probes. Designed as a logic module for eventual integration into a SCADA training dashboard.

🚀 Overview

This simulation mimics how a pump behaves in automatic mode, turning on when the tank level is low and off when the level is high. It includes safety logic to prevent rapid restarts and uses a hysteresis-like control scheme.

This standalone logic is ideal for SCADA training environments, educational purposes, or verifying logic before deployment.

🔧 Features

Simulated tank level rise and fall

Simple ON/OFF control based on setpoints

Visual output via matplotlib

Colored terminal feedback with colorama

Modular and ready to integrate into larger SCADA systems

📊 Visualization
[Plot](https://github.com/user-attachments/assets/bb817cc0-5047-4c37-8caa-e89cb8758387)


The script produces a plot showing:

Tank levels over simulated time

Setpoints for pump ON and OFF triggers





📁 Project Structure

pump-auto-sim/
├── src/
│   └── pump_simulation.py     # Main logic and visualization script
├── LICENSE                    # MIT License
├── requirements.txt          # Required Python packages
├── README.md                 # This file

📦 Installation

Clone the repository:

git clone https://github.com/yourusername/pump-auto-sim.git
cd pump-auto-sim

Install the dependencies:

pip install -r requirements.txt

Run the simulation:

python src/pump_simulation.py

🧪 Requirements

matplotlib==3.8.4
colorama==0.4.6

(Include this in a requirements.txt file.)

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

🙋‍♂️ Author & Intent

Created by an experienced water treatment operator and automation enthusiast as a logic simulation tool for SCADA training and validation.

🔮 Future Ideas

CSV or log file outputs for pump activity

Unit tests for logic verification

Real-time GUI integration for training dashboards

MQTT or Modbus simulation layer for remote feedback

Feel free to fork, contribute, or use this simulation to enhance your own training or SCADA development projects!

