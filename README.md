# Differential-Amplifier-5T-OTA-Single-Stage-OPAMP-
A differential amplifier or 5T-OTA amplifies the difference between inputs while rejecting noise, with the single-stage Op-Amp offering high gain and simplicity. This project enhances skills in low-noise, precision analog design, crucial for applications in sensors, ADCs, and signal processing, emphasizing low power and compactness.


Welcome to the project repository for the Single-Stage Operational Amplifier (Op-Amp) design. This project explores the fundamental aspects of analog circuit design, focusing on the implementation and analysis of a single-stage Op-Amp.

## Table of Contents

𝟭. 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄  
𝟮. 𝗨𝗻𝗱𝗲𝗿𝘀𝘁𝗮𝗻𝗱𝗶𝗻𝗴 𝟲𝗧 𝗢𝗧𝗔, 𝗦𝗶𝗻𝗴𝗹𝗲-𝗦𝘁𝗮𝗴𝗲 𝗢𝗽-𝗔𝗺𝗽, 𝗮𝗻𝗱 𝗗𝗶𝗳𝗳𝗲𝗿𝗲𝗻𝘁𝗶𝗮𝗹 𝗔𝗺𝗽𝗹𝗶𝗳𝗶𝗲𝗿  
𝟯. 𝗖𝗶𝗿𝗰𝘂𝗶𝘁 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄  
𝟰. 𝗖𝗶𝗿𝗰𝘂𝗶𝘁 𝗗𝗲𝘀𝗰𝗿𝗶𝗽𝘁𝗶𝗼𝗻  
𝟱. 𝗣𝗿𝗼𝗷𝗲𝗰𝘁 𝗪𝗼𝗿𝗸 𝗗𝗲𝘀𝗶𝗴𝗻𝗶𝗻𝗴 𝗦𝗶𝗻𝗴𝗹𝗲 𝗦𝘁𝗮𝗴𝗲 𝗢𝗣𝗔𝗠𝗣  
𝟲. 𝗗𝗲𝘀𝗶𝗴𝗻 𝗦𝗽𝗲𝗰𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀  
𝟳. 𝗖𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗶𝗻𝗴 𝗗𝗖 𝗣𝗮𝗿𝗮𝗺𝗲𝘁𝗲𝗿𝘀  
𝟴. 𝗠𝗶𝗻 𝗮𝗻𝗱 𝗠𝗮𝘅 𝗧𝗵𝗿𝗲𝘀𝗵𝗼𝗹𝗱 𝗩𝗮𝗹𝘂𝗲𝘀  
𝟵. 𝗙𝘂𝗹𝗹 𝗖𝗶𝗿𝗰𝘂𝗶𝘁 𝗗𝗲𝘀𝗶𝗴𝗻 𝗮𝗻𝗱 𝗪𝗶𝗿𝗲 𝗖𝗼𝗻𝗻𝗲𝗰𝘁𝗶𝗼𝗻𝘀  
𝟭𝟬. 𝗔𝗖 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀 (𝗕𝗼𝗱𝗲 𝗣𝗹𝗼𝘁)  
𝟭𝟭. 𝗦𝗹𝗲𝘄 𝗥𝗮𝘁𝗲 𝗖𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗶𝗼𝗻  
𝟭𝟮. 𝗖𝗠𝗥𝗥 𝗣𝗹𝗼𝘁  
𝟭𝟯. 𝗣𝗦𝗥𝗥 𝗣𝗹𝗼𝘁   
𝟭𝟰. 𝗡𝗼𝗶𝘀𝗲 𝗣𝗹𝗼  

### Project Overview
The single-stage Op-Amp is a fundamental building block in analog electronics, combining simplicity and versatility. It is characterized by its ability to provide high gain, efficient power consumption, and robust performance in a compact form factor. This design focuses on creating an Op-Amp that can amplify signals with precision and reliability, catering to applications like signal amplification, filtering, and sensor interfaces.

With its essential role in various systems, the single-stage Op-Amp not only enables the amplification of weak signals but also serves as a stepping stone for understanding complex multi-stage designs, making it invaluable for learners and professionals alike.

### Understanding 6T OTA, Single-Stage Op-Amp, and Differential Amplifier
The 6-Transistor Operational Transconductance Amplifier (6T OTA), Single-Stage Operational Amplifier (Op-Amp), and Differential Amplifier are closely related analog circuit topologies, sharing similar principles while catering to distinct applications. This section explains their similarities and differences, providing clarity on their usage and functionality.

#### 1. Commonality
All three circuits are built around the concept of differential amplification, where the difference between two input signals is amplified while rejecting common-mode noise. They share key design elements:

**Input Stage:** A differential pair of transistors.
**Load Stage:** Typically uses resistive or current mirror loads to convert the differential current into a voltage or further amplify it.
**Biasing:** Requires a steady current source, often implemented using transistors.
These circuits are often the foundation of many analog designs, serving as the first stage in multi-stage amplifiers or standalone low-power solutions.

#### 2. Differences in Design and Purpose
**6T OTA:** This circuit provides a current output proportional to the voltage difference at the inputs, functioning as a transconductance amplifier. It is designed with 6 transistors, including an NMOS current mirror as the tail current source. The 6T OTA is commonly used in applications like filters, modulators, and low-power analog designs due to its current-output nature.

**Single-Stage Op-Amp:** The single-stage operational amplifier amplifies the voltage difference between its inputs and provides a single-ended voltage output. It typically consists of 5 transistors and is used for applications like signal amplification and low-frequency circuits, where simplicity and compactness are prioritized.

**Differential Amplifier:** A basic circuit for amplifying the voltage difference between two inputs, the differential amplifier can have a single-ended or differential output. It often serves as a foundational building block in sensor signal processing and analog-to-digital converters (ADCs), emphasizing basic gain with fewer components.

### Circuit Overview
The 6-transistor OTA circuit consists of:

**Input Differential Pair:** Two NMOS transistors that process the differential input signals.
**Current Mirror Load:** Two PMOS transistors form the current mirror, which improves the gain and maintains balanced current flow.
**Output Stage:** The current mirror at the output ensures efficient current transfer and high linearity.
**NMOS Current Mirror as Tail Current Source:** Instead of a conventional constant tail current source, an NMOS-based current mirror is used to provide the differential pair with a steady bias current.

.........................................![image](https://github.com/user-attachments/assets/5db0b080-87cf-43d2-85de-1725c8e2cac0)


### Circuit Description
**1. Input Stage (Differential Pair):**
Two NMOS transistors M1 and M2 are used to create a differential pair.
The input signals Vin+ and Vin- are applied to their gates.
The differential pair amplifies the difference between the input signals while rejecting the common-mode signals, ensuring noise immunity.

**2. Tail Current Source (NMOS Current Mirror):**
The NMOS transistors M5 and M6 form a current mirror, replacing the conventional constant current source.
This current mirror sets the bias current for the differential pair, maintaining a steady operating point for M1 and M2 Using an NMOS current mirror as a tail source improves current matching and enables better biasing in low-voltage designs.

**3. Load Stage (PMOS Current Mirror):**
The PMOS transistors M3 and M4 form a current mirror that acts as the load for the differential pair.
The current mirror reflects and balances the output currents from the differential pair.
This configuration improves the output impedance and gain of the OTA.

**4. Output Node:**
The output current is taken from the drain of M3 and M4 depending on the design.
The circuit outputs a current proportional to the difference between the input signals, fulfilling the transconductance function.

## Project Work Designing of Single Stage OPAMP
## 1. Declaring design specifications.
We are required to design an Single stage OPAMP having load capacitor CL = 2pF with the 1.1 volts power supply. I used the TSMC 40nm node technology for this project. An OPAMP was designed to best meet the following specificatons:

- 𝗗𝗶𝗳𝗳𝗲𝗿𝗲𝗻𝘁𝗶𝗮𝗹 𝘃𝗼𝗹𝘁𝗮𝗴𝗲 𝗴𝗮𝗶𝗻: 𝗔𝘃𝗱 ≥ 𝟯𝟬𝗱𝗕.
- 𝗼𝗽𝗲𝗿𝗮𝘁𝗶𝗻𝗴 𝘃𝗼𝗹𝘁𝗮𝗴𝗲 𝘃𝗱𝗱 = 𝟭.𝟭 𝘃
- 𝗦𝗹𝗲𝘄 𝗿𝗮𝘁𝗲: 𝗦𝗥 ≥ 𝟱 𝗩/μ𝗦.
- 𝗜𝗻𝗽𝘂𝘁 𝗰𝗼𝗺𝗺𝗼𝗻 𝗺𝗼𝗱𝗲 𝗿𝗮𝗻𝗴𝗲: 𝗜𝗖𝗠𝗥 (𝟲𝟱𝟬𝗺 , 𝟵𝟬𝟬𝗺)
- 𝗨𝗻𝗶𝘁𝘆 𝗚𝗮𝗶𝗻-𝗯𝗮𝗻𝗱𝘄𝗶𝗱𝘁𝗵: 𝗚𝗕 ≥ 𝟭𝟬𝗠𝗛𝘇 𝘄𝗶𝘁𝗵 𝗮 𝟮𝗽𝗙 𝗹𝗼𝗮𝗱 𝗰𝗮𝗽𝗮𝗰𝗶𝘁𝗮𝗻𝗰𝗲.
- 𝗣𝗵𝗮𝘀𝗲 𝗠𝗮𝗿𝗴𝗶𝗻: 𝗳(𝗚𝗕) ≥ 𝟲𝟬° 𝘄𝗶𝘁𝗵 𝗮 𝟮𝗽𝗙 𝗹𝗼𝗮𝗱 𝗰𝗮𝗽𝗮𝗰𝗶𝘁𝗮𝗻𝗰𝗲.
- 𝗣𝗼𝘄𝗲𝗿 𝗱𝗶𝘀𝘀𝗶𝗽𝗮𝘁𝗶𝗼𝗻: 𝗣𝗱𝗶𝘀𝘀 ≤ 𝟭𝗺𝗪.

## 2. calculating the DC parameter using Dc analysis of nmos and pmos (μpCox and μnCox)

upcox = 115u , 
uncox = 285u

............................![betaeffctive](https://github.com/user-attachments/assets/173a8a26-fb37-4621-9ef3-be2dd1d0dc9e)


## 3. calculating the min and max threshold value of m1 and m3 mos

Vtp = 485mV ,
Vtn = 460mV

## 4. Designing full circuit and make proper wire connection

![Diffn_ckt](https://github.com/user-attachments/assets/d5030d9e-9f65-4e84-a692-3c79f46b8052)

![Diffn_ckt _cmrrjpg](https://github.com/user-attachments/assets/23797f33-3a41-4dd0-a43d-9b67d18e2171)


## 5. Ac analysis ( Bode plot) 
**DCGain=27.02dB , GBW = 8.63MHz and Phase Margin = 92 , Bandwidth=368.3kHz**

.....................![gainand Phaseplot](https://github.com/user-attachments/assets/131aa519-5cf0-4d27-b9d3-5b1b6b37b162)



## 6. Calculation of Slew Rate.
We know that according to target specifications the slew rate should be 5V/μsec. Lets see how much we are actually getting. Below is the setup for calculation of SR. I connected inverting terminal to output in unity gain closed loop form and provided pulse input at the non-inverting terminal and observed the transient reponse.

................................![transt](https://github.com/user-attachments/assets/8743377c-10d9-40b8-8c04-abb7339c8647)


from the wave output we get 𝗦𝗥 = 𝟰.𝟲𝟭 𝘃/𝘂𝘀𝗲𝗰 

## 7. CMRR Plot

...............................![Cmrr](https://github.com/user-attachments/assets/5ea53a38-0f82-4e5a-abbe-6bbb71f6d031)



## 8. PSRR Plot
..............................![psrr](https://github.com/user-attachments/assets/47ed3a3a-6cd2-4727-890f-e594431c4a36)



## 9. Noise Plot

..............................![noise](https://github.com/user-attachments/assets/a6e62810-aac6-46c3-bc48-775a923f10d5)

