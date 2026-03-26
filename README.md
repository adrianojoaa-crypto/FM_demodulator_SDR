## FM Signal Demodulaton Using Software Defined Radio Techniques 

*This project implements a Software Defined Radio (SDR) post-processing pipeline to extract and demodulate multiple FM broadcast stations from a wideband IQ recording using digital signal processing techniques.*
 
*By Adriano Giles.*

---

## Overview

1. **Objective** 
2. **Structure**
3. **Procedure**
4. **Results**
5. **Discussion**
6. **Conclusion**

---

## Objective

The objective of this project was to realize a digital demodulator capable of maintaining phase linear in the frequency domain and minimizing delay in the time domain to extract radio broadcast signals with minimimal distortion. In a world where digital processing of signals has become the standard, it is imperative to understand and acquire the abilities necessary to implement these systems.

---

## Repository Structure

```
.
├── pick_radio_station.py      # Allows for interaction with a user (determines what station will be demodulated)
├── fm_demodulator             # Contains the structure of the demodulator
├── test_hamming_windows       # Contains tests 
└── README.md                  # (This file)
```

---
