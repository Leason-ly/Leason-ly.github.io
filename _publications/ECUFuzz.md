---
title: "Structure-Aware, Diagnosis-Guided ECU Firmware Fuzzing"
collection: publications
permalink: /publication/ECUFuzz
excerpt: 'Firmware, ECU Firmware Fuzzing, Serial Peripheral Interface, Diagnostic Feedback'
date: 2025-06-25
venue: 'Proceedings of the 34rd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA ’25)'
paperurl: 'http://leason-ly.github.io/files/issta25-chen-ecufuzz.pdf'
citation: 'Qicai Chen, Kun Hu, Sichen Gong, Bihuan Chen, Zikui Kong, Haowen Jiang, Bingkun Sun, You Lu, and Xin Peng. 2025. Structure-Aware, Diagnosis-Guided ECU Firmware Fuzzing. Proc. ACM Softw. Eng. 2, ISSTA, Article ISSTA039 (July 2025), 23 pages. https://doi.org/10.1145/3728914'
---

Electronic Control Units (ECUs), providing a wide range of functions from basic control functions to safety-critical functions, play a critical role in modern vehicles. Fuzzing has emerged as an effective approach to ensure the functional safety and automotive security of ECU firmware. However, existing fuzzing approaches focus on the inputs from other ECUs through external buses (e.g., CAN), but neglect the inputs from internal peripherals through on-board buses (e.g., SPI). Due to the restricted input space exploration, they fail to comprehensively fuzz ECU firmware. Moreover, existing fuzzing approaches often lack visibility into ECU firmware’ internal states but rely on limited feedback (e.g., message timeouts or hardware indicators), hindering their effectiveness.

To address these limitations, we propose a structure-aware, diagnosis-guided framework, EcuFuzz, to comprehensively and effectively fuzz ECU firmware. Specifically, EcuFuzz simultaneously considers externalbuses (i.e., CAN) and on-board buses (i.e., SPI). It leverages the structure of CAN and SPI to effectively mutate CAN messages and SPI sequences, and incorporates a dual-core microcontroller-based peripheral emulator to handle real-time SPI communication. In addition, EcuFuzz implements a new feedback mechanism to guide the fuzzing process. It leverages automotive diagnostic protocols to collect ECUs’ internal states, i.e., error-related variables, trouble codes, and exception contexts. Our compatibility evaluation on ten ECUs from three major Tier 1 automotive suppliers has indicated that our framework is compatible with nine ECUs. Our effectiveness evaluation on three representative ECUs has demonstrated that our framework detects nine previously unknown safety-critical faults, which have been patched by technicians from the suppliers.