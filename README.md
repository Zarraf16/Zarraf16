<div align="center">

<img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/837772c262f1ed756658ff8a157dd95027ff31d4/assets/flightdeck.svg" width="100%" alt="Zarraf Alam Fahmid — ivory and red motorsport banner"/>

**COMPUTER ENGINEERING @ KETTERING UNIVERSITY**

Hardware, firmware, and the systems that connect them.

[Explore builds](#the-project-garage) · [Open the workbench](#tools-of-the-trade) · [Read the reports](#engineering-documentation)

</div>

---

### Behind the work

I’m **Zarraf Alam Fahmid**, a Computer Engineering student in Michigan. I design circuits, integrate sensors, write code, and work through the practical problems that appear when separate components become a system.

My background includes network troubleshooting, board-level rework, and AVR telemetry over UART. At the **Schoolcraft Engineering Club**, I collaborated on an autonomous/manual F1-style RC vehicle and an automated water-filtration system. My individual projects explore PCB design, analog audio, and control using logic ICs.

**Looking for co-ops in embedded systems, automotive electronics, firmware, and hardware testing.**

## The project garage

Click a card to open the repository. Each animation illustrates the project’s engineering focus.

<table>
<tr>
<td width="50%" valign="top"><a href="https://github.com/Zarraf16/Autonomous-Car"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/build-car.svg" width="100%" alt="DUAL-MODE F1 CAR — CLUB COLLABORATION"/></a></td>
<td width="50%" valign="top"><a href="https://github.com/Zarraf16/Water-Filter-Sensor-Module"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/build-water.svg" width="100%" alt="WATER FILTRATION — CLUB COLLABORATION"/></a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/Zarraf16/Arduino-LED-Shield-PCB"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/build-shield.svg" width="100%" alt="ARDUINO LED SHIELD — INDIVIDUAL DESIGN"/></a></td>
<td width="50%" valign="top"><a href="https://github.com/Zarraf16/Lm386-Audio-amplifier"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/build-audio.svg" width="100%" alt="LM386 AMPLIFIER — INDIVIDUAL BUILD"/></a></td>
</tr>
<tr>
<td width="50%" valign="top"><a href="https://github.com/Zarraf16/IC-Based-Line-Follower"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/build-line.svg" width="100%" alt="IC LINE FOLLOWER — INDIVIDUAL BUILD"/></a></td>
<td width="50%" valign="top"><a href="https://github.com/Zarraf16/Automatic-Plant-Watering-System"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/build-plant.svg" width="100%" alt="PLANT WATERING — PROTOTYPE"/></a></td>
</tr>
</table>

**Vehicle testing:** video timing over a **2.65 m distance** estimated **19.8 mph** for the 2015 model and **22.2 mph** for the 2023 model, with a **10% uncertainty allowance**. These are model-specific speed estimates.

**My RC-car PCB contribution:** a compact two-layer layout, **35 mil power traces**, GND stitching vias, and integration with the vehicle’s electronics. The separate **Arduino LED shield** project uses nine LED channels and a potentiometer; its schematic and board previews are available in that repository.

## Tools of the trade

<div align="center">

<img src="https://skillicons.dev/icons?i=c,python,matlab,bash,git,github,vscode,arduino&amp;perline=8" alt="C, Python, MATLAB, Bash, Git, GitHub, VS Code and Arduino" />

<br/><br/>

<img src="https://img.shields.io/badge/EasyEDA-PCB_Design-182338?style=for-the-badge&amp;labelColor=54418a&amp;color=182338" alt="EasyEDA PCB design"/>
<img src="https://img.shields.io/badge/SolidWorks-3D_CAD-182338?style=for-the-badge&amp;labelColor=a13e42&amp;color=182338" alt="SolidWorks 3D CAD"/>
<img src="https://img.shields.io/badge/LTspice-Simulation-182338?style=for-the-badge&amp;labelColor=3e668a&amp;color=182338" alt="LTspice simulation"/>
<img src="https://img.shields.io/badge/GDB-Debugging-182338?style=for-the-badge&amp;labelColor=477c67&amp;color=182338" alt="GDB debugging"/>

</div>

<table>
<tr>
<td width="50%"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/tools-code.svg" width="100%" alt="SOFTWARE WORKBENCH"/></td>
<td width="50%"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/tools-design.svg" width="100%" alt="DESIGN & SIMULATION"/></td>
</tr>
<tr>
<td width="50%"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/tools-embedded.svg" width="100%" alt="EMBEDDED CONTROL"/></td>
<td width="50%"><img src="https://raw.githubusercontent.com/Zarraf16/Zarraf16/main/assets/tools-lab.svg" width="100%" alt="HARDWARE LAB"/></td>
</tr>
</table>

### From a signal to a working system

**SENSE** — IR arrays, cameras, water-quality and soil-moisture sensors  
**COMPUTE** — C, Python, MATLAB, AVR microcontrollers, and PID control  
**ACT** — steering servos, ESCs, motor drivers, relays, and pumps  
**VALIDATE** — debugging, hardware inspection, testing, and documentation

## Engineering documentation

| Build | Open documentation |
|---|---|
| Dual-mode F1 RC car | [Engineering report](https://github.com/Zarraf16/Autonomous-Car/blob/main/F1_RC_Car_Engineering_Report.pdf) · [Code and hardware](https://github.com/Zarraf16/Autonomous-Car) |
| Automated water filtration | [Engineering report](https://github.com/Zarraf16/Water-Filter-Sensor-Module/blob/main/Smart_Water_Filtration_Engineering_Report.pdf) · [Code](https://github.com/Zarraf16/Water-Filter-Sensor-Module) |
| Arduino LED shield | [Design report](https://github.com/Zarraf16/Arduino-LED-Shield-PCB/blob/main/Arduino_LED_Shield_PCB_Report.pdf) · [Schematic and 3D previews](https://github.com/Zarraf16/Arduino-LED-Shield-PCB#schematic) |
| LM386 audio amplifier | [Project report](https://github.com/Zarraf16/Lm386-Audio-amplifier/blob/main/LM386%20audio%20amplifier.pdf) · [Circuit details](https://github.com/Zarraf16/Lm386-Audio-amplifier) |

<details>
<summary><strong>Inside the Arduino LED shield — actual design preview</strong></summary>
<br/>
<img src="https://raw.githubusercontent.com/Zarraf16/Arduino-LED-Shield-PCB/main/images/board-preview.png" width="700" alt="Arduino LED shield PCB assembly preview from the design report"/>
</details>

### Next on the bench

Strengthening embedded C, debugging, control systems, and hardware validation at Kettering. I’m also a robotics-club member, with longer-term interests in **quantum hardware and quantum control**.

<div align="center">

---

**TRACE THE SIGNAL. UNDERSTAND THE SYSTEM. BUILD SOMETHING THAT WORKS.**

<sub>ZF / HARDWARE × FIRMWARE × MOBILITY</sub>

</div>
