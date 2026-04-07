# WeMo Switch + Motion Hacking

## Target Information

**Manufacturer:** Belkin

**Model:** F7C028

## Test-Equipment
 
**Multimeter:** ASTRO AI AM33D

**Logic Analyzer:** Comidox USB Logic Analyzer

**USB to UART Adapter:** Silicon Labs CP210x UART Bridge

**Software:** 
- Sigrok Pulsview (for logic captures)
- Screen

**Hardware**
- T7 Torx screwdriver
- Phillips Head screwdriver

## Visual Inspection

Inspected exterior of the switch, label on the back contained FCC ID info and other details.

![switch_front](https://github.com/user-attachments/assets/d8bfea4e-e7ea-42fa-9a5c-63dc7ff3cf42)

![switch_back_marked](https://github.com/user-attachments/assets/2b8c2b84-c73e-406b-bc58-8e0c713ef2d6)

**FCC ID:** K7SF7C028 <br>
**Input:** 120V - /15A/60Hz/1800W

Switch case screws were triangle shaped, required T7 Torx screwdriver to remove. Two of the screws were hidden underneath the sticker.

![switch_back_unscrew_marked](https://github.com/user-attachments/assets/fbb4846e-1217-4565-8b74-336f6b40be7e)

![torx_driver](https://github.com/user-attachments/assets/5522a3bd-6a50-4956-94ed-247b43fd7444)

Two PCBs located inside. One was for the power components. This was held down by two phillips head screws. Also noted, there are four wires holding together the PCBs.

![switch_open_marked](https://github.com/user-attachments/assets/ec85b6d7-9b84-4425-b8ba-a3be4e901b90)

The other for the WiFi board. Noted three chips of interests on the WiFi board; one on the front, two on the back. This was only clipped down to the case.

![wifi_board_front](https://github.com/user-attachments/assets/56c9fc03-875f-478c-96fe-4043aca530a0)

![wifi_board_back](https://github.com/user-attachments/assets/98cd504e-0e53-489c-b3ab-4949be12b1e9)

**System-on-Chip (SoC):** Ralink, RT5350F. [Datasheet](https://github.com/la4gia/hardware_hacking_notes/blob/main/belkin_wemo_f7c028/datasheets/RT5350.pdf)

![SoC](https://github.com/user-attachments/assets/1b3b38bc-4483-4eb3-b376-ac434f1e048e)

**SRAM:** EtronTech, EM63A165T5-6IG. [Datasheet](https://github.com/la4gia/hardware_hacking_notes/blob/main/belkin_wemo_f7c028/datasheets/EM63A165TS-5IG.PDF)

![sram](https://github.com/user-attachments/assets/818e8bd2-ab9f-4002-9d02-40492ebf2682)

**Flash/ROM:** MXIC, MX25L12835EM1-10G. [Datasheet](https://github.com/la4gia/hardware_hacking_notes/blob/main/belkin_wemo_f7c028/datasheets/MX25L12835E.PDF)

![rom](https://github.com/user-attachments/assets/f47e141b-ccbd-41c0-9901-6bd64e184f6c)

