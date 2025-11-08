# DFU Risk Simulator
**Vladimir Burzanović, MD**
General Surgeon + Angiology Subspecialty → HealthTech

**Phone-based DFU self-check**: Doppler + Photo Temp + **Orpyx-style Pressure** → **% risk + urgent alarm**

**Live Demo**: [Run in Browser (Binder)](https://mybinder.org/v2/gh/Boogieman237/dfu-risk-sim/main?filepath=dfu_risk_score.ipynb)

---

## Features
- Doppler waveform (triphasic / biphasic / monophasic)
- Temp diff (°C) from foot photo
- Pressure (kPa) — **Orpyx Sensory Insole proxy**
- Ulcer sign (yes/no)
→ **100-point risk % + 3-tier alert**

---

## Use Case (Aseer Central Hospital)
> *Monophasic + 2.5°C + 220 kPa + ulcer → **100% → URGENT: See MD NOW***

---

## Doppler Waveform Classifier (Phone Audio → Auto-Risk)
→ [Run in Binder](https://mybinder.org/v2/gh/Boogieman237/dfu-risk-sim/main?filepath=doppler_classifier.ipynb)  
→ Triphasic / Biphasic / Monophasic → feeds DFU risk score
## Next
- Real Orpyx insole API integration (pilot pending)
- OpenCV ulcer detection from photo
- CSV export for teleradiology

[Email Orpyx](mailto:info@orpyx.com) | [LinkedIn](https:linkedin.com/in/vladimir-burzanović-52a8b927//)
