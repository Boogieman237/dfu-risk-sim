# DFU Risk Simulator  
**Vladimir Burzanović, MD**  
General Surgeon + Angiology Subspecialty → HealthTech  

**Phone-based DFU self-check**: Doppler waveform + foot photo temp + **Orpyx-style pressure/temp proxy** → **% risk + urgent alarm**  

Live demo: [Run in Browser (Binder)](https://mybinder.org/v2/gh/Boogieman237/dfu-risk-sim/main?filepath=dfu_risk_score.ipynb)  

---

## Features  
- **Doppler**: triphasic / biphasic / monophasic  
- **Temp diff** (°C) from foot photo (IR proxy)  
- **Pressure** (kPa) — inspired by **Orpyx Sensory Insoles**  
- **Ulcer sign** (yes/no)  
→ **Composite risk % + 3-tier alert**  

---

## Use Case  
KSA diabetic foot unit (Aseer Central Hospital):  
> *Monophasic + 2.5°C hotspot + 220 kPa + ulcer sign → **100% risk → URGENT: See MD NOW***  

---

## Next  
- Integrate real Orpyx insole data (pilot pending)  
- Add photo AI (ulcer detection via OpenCV)  
- Export CSV for teleradiology  

[Contact for pilot](mailto:info@orpyx.com) | [LinkedIn](https://linkedin.com/in/vladimir-burzanović-52a8b927)
