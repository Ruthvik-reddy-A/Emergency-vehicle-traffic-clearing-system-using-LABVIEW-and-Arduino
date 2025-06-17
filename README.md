<!--![image](https://github.com/Ruthvik-reddy-A/EMRGENCY-VEHICLE-TRAFFIC-CLEARING-SYSTEM-USING-LABVIEW-AND-ADUINO/assets/73007037/a18c46c1-55c6-4cab-9b8d-145b31cdf823)-->

# 🚨 Emergency Vehicle Traffic Clearing System Using Arduino and NI LabVIEW


# 📌 Objective

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

## 🔩 Bill of Materials

| S.No | Component                 | Quantity | Cost (INR) |
|------|---------------------------|----------|------------|
| 1    | Breadboard                | 2        | 200.00     |
| 2    | Jumper wires              | 1 pack   | 90.00      |
| 3    | Arduino Uno + USB Cable  | 1        | 900.00     |
| 4    | Resistor (4.7kΩ)          | 3        | 6.00       |
| 5    | LEDs (Red - 3, Green - 3) | 6        | 6.00       |
| 6    | IR Receiver (PT333-3B)    | 3        | 30.00      |
| 7    | IR Emitter (PT333-3C)     | 1        | 10.00      |
| 8    | 9V Battery                | 1        | 50.00      |
| 9    | Battery Clip             | 1        | 8.00       |
|      | **Total**                |          | **1,300.00** |

## 👨‍💻 Team Contributions

- **A. Ruthvik Reddy** – Arduino Development, Report, Presentation
- **B. K. V. Surya** – LabVIEW Development, Arduino Integration
- **P. V. Pavan Kumar Varma** – LabVIEW, Report Documentation

## 🙌 Reflections

> _"It’s not easy to find good team members, but I was lucky to work with B.K.V. Surya."_  
> _"I got to work with good teammates and learned LINX LabVIEW-Arduino interfacing."_  
> — Pavan Varma

## 📷 Demo & Media

*Add images or video links showing the prototype in action*

## 📁 File Structure

