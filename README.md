# 🎶 3-Way Crossover Filter Design (LTspice)

This repository contains the design, simulation, and analysis of a **3-way crossover filter** for audio systems, implemented and tested in **LTspice**.  

Crossover networks are essential in **headphones and speaker systems** to split the audio spectrum into frequency ranges handled by dedicated drivers:
- **Woofer** → Low frequencies  
- **Midrange** → Mid frequencies  
- **Tweeter** → High frequencies  

By ensuring each driver only processes its intended band, distortion is reduced and sound quality is improved.  

---

## 📂 Repository Structure

---

## 🔧 Filters Implemented

### 1. Woofer Low-Pass Filter
- Passes low-frequency range  
- Attenuates mid + high frequencies  
- Cutoff frequency: *X Hz* (from datasheet)  
- Roll-off: *Y dB/octave*  

📷 Woofer  
![Woofer](Images/Woofer.png)  

📊 Frequency Response  
![Woofer Response](Results/Woofer_Response.png)  

---

### 2. Midrange Band-Pass Filter
- Passes mid-frequency range  
- Blocks very low and very high frequencies  
- Lower cutoff: *X Hz*  
- Upper cutoff: *Y Hz*  
- Roll-off slopes: *Z dB/octave*  

📷 Midrange  
![Midrange](Images/Midrange.png)  

📊 Frequency Response  
![Midrange Response](Results/Midrange_Response.png)  

---

### 3. Tweeter High-Pass Filter
- Passes high-frequency range  
- Attenuates mid + low frequencies  
- Cutoff frequency: *X Hz*  
- Roll-off: *Y dB/octave*  

📷 Tweeter  
![Tweeter](Images/Tweeter.png)  

📊 Frequency Response  
![Tweeter Response](Results/Tweeter_Response.png)  

---

## 🚀 Usage Instructions

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/3-Way-Crossover-Filter.git

