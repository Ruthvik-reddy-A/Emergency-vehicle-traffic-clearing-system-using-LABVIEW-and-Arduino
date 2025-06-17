<!--![image](https://github.com/Ruthvik-reddy-A/EMRGENCY-VEHICLE-TRAFFIC-CLEARING-SYSTEM-USING-LABVIEW-AND-ADUINO/assets/73007037/a18c46c1-55c6-4cab-9b8d-145b31cdf823)-->

# 🚨 Emergency Vehicle Traffic Clearing System Using Arduino and NI LabVIEW


## 📌 Objective

To design and implement a prototype that:
- Detects emergency vehicles using IR transmitters.
- Automatically changes the traffic signal to GREEN on the approaching path.
- Switches other signals to RED, minimizing traffic restrictions.

## ⚙️ Working Principle

- An **IR emitter** is installed on the emergency vehicle.
- An **IR receiver sensor** is embedded at traffic signal poles.
- When an IR signal is detected by the receiver, the Arduino sends a signal to LabVIEW.
- Based on the logic programmed in LabVIEW, the **respective signal turns GREEN** and all others turn RED.

## 🧩 Circuit Diagram

![image](https://github.com/user-attachments/assets/5d8d7a77-4fcd-44f7-9f42-900dc10532a5)

## 🧠 Flowchart

![image](https://github.com/user-attachments/assets/63bbf526-b376-4fdc-9b9a-bb95378b57f8)

## 💡 Results

The system successfully detects emergency vehicles and responds by switching the relevant traffic light to GREEN, allowing quick and unobstructed passage.

![image](https://github.com/user-attachments/assets/c3b5f132-8531-4e58-a5b2-9fa3bb88ec7b)

## ✅ Conclusion

This prototype provides a **cost-effective and practical solution** to reduce delays faced by emergency vehicles. It has demonstrated its effectiveness in simulated scenarios using Arduino and LabVIEW.

## ⚠️ Limitations

- In case multiple emergency vehicles arrive from different directions simultaneously, no priority logic is currently implemented.
- The system assumes line-of-sight IR communication and a clear signal.

## 🔧 Scope for Improvement

1. **GPS-based tracking** for route optimization and pre-clearing traffic.
2. **Priority logic** for handling multiple emergency vehicles.
3. Integration with **traffic police alerts** for better route management.

## 🌍 Impact

According to studies, **30% of ambulance-related deaths** are caused due to traffic delays. This system aims to **significantly reduce response time**, potentially saving many lives.




