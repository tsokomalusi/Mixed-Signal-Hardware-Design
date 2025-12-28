# Mixed-Signal-Hardware-Design

## 📌 Project Summary
This repository contains a mixed-signal hardware design project covering system-level design, schematic capture, analog simulation, and PCB layout.  
The project demonstrates best practices in analog/digital partitioning, component selection, simulation-driven design, and manufacturable PCB layout.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🧰 Tools Used
- **KiCad** – Schematic capture and PCB design  
- **LTSpice** – Analog circuit simulation  
- **STM32CubeIDE** – MCU pinout planning  
- **draw.io** – System block diagram
- **git and github** - version control system
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🧱 System Block Diagram

<img width="843" height="405" alt="block_diagram" src="https://github.com/user-attachments/assets/8b7f9496-2616-4fa9-a641-4d79e61946c4" />

Refined version
  
<img width="853" height="481" alt="block_diagram_refined" src="https://github.com/user-attachments/assets/2bce83ed-b713-46d3-b661-487e8f5b001a" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📐 Schematic Design

Root Sheet
<img width="963" height="685" alt="root" src="https://github.com/user-attachments/assets/3625d398-3268-436a-9736-85ebfcaaa721" />

Power circuitry
<img width="964" height="672" alt="power" src="https://github.com/user-attachments/assets/3ee1d34c-0159-4ad3-a6b7-ff2a13fbf5ff" />

MCU circuitry
<img width="968" height="681" alt="mcu" src="https://github.com/user-attachments/assets/1225ea4a-be6b-42f5-afc0-0d9f20b3f33e" />

ADC circuirty
<img width="964" height="676" alt="adc" src="https://github.com/user-attachments/assets/b4ca1268-3c4f-4863-9ea4-28fe4c4d025d" />

DAC circuitry
<img width="968" height="677" alt="dac" src="https://github.com/user-attachments/assets/a1e16953-524a-42c2-bc6d-3f37d5181a88" />

Key design considerations:
- Proper decoupling and grounding
- Separation of analog and digital domains
- Power integrity and signal integrity

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🧩 PCB Layout

###  PCB All Layers
<img width="542" height="547" alt="PCB_LAYOUT" src="https://github.com/user-attachments/assets/9f245c09-d3aa-4ac6-ae80-41007ddf267d" />

### Top Layer
<img width="527" height="550" alt="PCB_TOP" src="https://github.com/user-attachments/assets/3a0b897b-3f6c-4a99-b84d-34ac79908ab1" />

### Bottom Layer
<img width="489" height="547" alt="PCB_BOTTOM" src="https://github.com/user-attachments/assets/de7185ed-765e-4ecc-adfb-6042a626f963" />

### 3D View
<img width="1170" height="666" alt="mixed_signal_hw_pcb_3D" src="https://github.com/user-attachments/assets/9a8b5e06-d461-48ee-a876-4fe2cf8964ee" />

PCB design highlights:
- Footprint creation
- Controlled impedance traces
- Avoiding: crosstalk, coupling, ground loops, inductance and radiation
- Via stitching, power puddles, keeping proper spacing between analog and digital circuits

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🔬 LTSpice Simulation

### AC Analysis Schematic
<img width="529" height="502" alt="ac_analysis" src="https://github.com/user-attachments/assets/39745037-eed5-463e-b88f-beca50ab7fca" />

### AC Analysis Response
<img width="523" height="615" alt="ac_analysis_response" src="https://github.com/user-attachments/assets/347d5798-be5e-4ab1-952d-19ae0dcc0fe4" />

### DC Operating Point Analysis
<img width="528" height="550" alt="dc_operating_point_analysis" src="https://github.com/user-attachments/assets/e21ac5d3-27f6-46ee-85d3-f7da3001c535" />

<img width="630" height="298" alt="DC_Operating_Point_Analysis" src="https://github.com/user-attachments/assets/ec5f391b-17d7-4bdc-8f33-b02e5110965c" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📜 License
This project is released for educational and portfolio purposes.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🙏 Acknowledgements

This project was developed as part of hands-on learning inspired by the course:

**“Mixed-Signal Hardware Design with KiCad”**  
Instructor: **Philip Salmony**  
Platform: **FEDEVEL Academy**  
Website: https://www.fedevel.com

