# kraky-lite2

Kraky-lite2 is the second version of the project kraky-lite.
The project Kraky-lite was inspired by Kraky, another project that i'm developing, and the focus
is to create a cheaper and DIY alternative for the flipper zero.

In this version the PCB is divided in 2 layers, one for power delivery and one for signal.

You can use it connected to a battery via the 18650 slot in the back or connected via usb-c.

I would soggest putting first all the smd commponents on the top layer, then the smd components on the bottom layer, and last the tht components.

I started this journey because i want to create a better version of my project kraky-lite, and i'm doing it by first using smd components instead of the 
tht modules so i can do some expirience soldering very small parts and stopping using pre made modules but recreating them myself.

---

# Main Components
| Function | Component |
|--------|----------|
| Logic board | **ESP32-S3 N16R8** |
| wifi | **nrf24l01** |
| Sub-GHz | **CC1101** |
| Battery charger | **CN3163** |
| Battery | -ion |
| microSD Slot | **MSD4A** |
| Buttons | 1 tactile buttons and a rotary encoder |
| Display | TFT Display |
| COM converter | **CH343P** |

---

# WIRING DIAGRAM

# ESP32

<img width="745" height="502" alt="Screenshot 2026-07-06 142850" src="https://github.com/user-attachments/assets/6c07a19a-2ca3-479c-824f-32ddc8cdaba1" />

 # POWER DELIVERY SYSTEM
 
<img width="1012" height="493" alt="Screenshot 2026-07-06 142901" src="https://github.com/user-attachments/assets/456cf19c-3c28-4349-a69c-c47645691584" />


# WIFI

<img width="784" height="466" alt="Screenshot 2026-07-06 142909" src="https://github.com/user-attachments/assets/f99190ed-3e24-4cd9-a511-54f5693effb5" />


# SUB-GHZ

<img width="838" height="484" alt="Screenshot 2026-07-06 142917" src="https://github.com/user-attachments/assets/fad7f64b-0e54-44a9-a41c-62f6d96c5a59" />


# MICROSD SLOT

<img width="317" height="381" alt="Screenshot 2026-07-06 142931" src="https://github.com/user-attachments/assets/4752f790-0f27-4302-bfc3-6b9cacdfd022" />


# DISPLAY

<img width="296" height="279" alt="Screenshot 2026-07-06 142923" src="https://github.com/user-attachments/assets/d2f19002-6ac4-451d-9ca2-7df4f513b26d" />


---

# PCB

<img width="1137" height="752" alt="Screenshot 2026-07-06 143114" src="https://github.com/user-attachments/assets/badd89fb-ba58-4e69-a907-c8f698f8bf48" />


---

# 3D render

<img width="1085" height="686" alt="Screenshot 2026-07-06 143213" src="https://github.com/user-attachments/assets/4ec374e4-ba68-4ba5-9cba-944bb518805a" />

---

# Responsible Use
Kraky-lite2 is built to make it easier for anyone to explore and understand how multifunction electronic devices work in everyday life. It’s not intended for bypassing security systems or breaking any laws.

All features are implemented with an educational and experimental focus.

---

# Tools Used

- KiCad 10
- Fusion360
- PlatformIO
---
## Contributing

All the Kraky's tools are an **open and educational project**.  
Feedback, suggestions, and improvements are always welcome.

---
