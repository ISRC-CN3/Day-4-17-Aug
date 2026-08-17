# matlab cmd git clone
```matlab
gitclone https://github.com/ISRC-CN3/Day-4-17-Aug.git
```

# cmd/powershell git clone

```matlab
git clone https://github.com/ISRC-CN3/Day-4-17-Aug.git
```
# have this folder where you will be working (live or local)

---
# Before stating have these files downloaded in lab folder

 - Day4_lab_graph.m
 - Day4_lab.mlx
 - fieldtrip-20250106 (folder)  [Download FieldTrip here](https://www.fieldtriptoolbox.org/download/)
 - Sample_MEG_Data.mat: [ Sample_MEG_Data.mat Onedrive](https://ulster-my.sharepoint.com/:u:/g/personal/butler-m13_ulster_ac_uk1/IQA9zQNfewN8Sb563qUGLmdoAQ505d5EKqeWLil6dDYjYXA?e=QRDiO5)
 - sourcemodelSample.mat [ sourcemodelSample.mat Onedrive](https://ulster-my.sharepoint.com/:u:/g/personal/butler-m13_ulster_ac_uk1/IQB85P4gyJUnSaGpteyc9U2HAR3-Gmk56ykcem2gO-8_C1s?e=X7o0am)
---
# once downloaded (and uploaded if on MATLAB live)

```matlab
addpath('fieldtrip-20250106')
ft_defaults
```




# MEG Frequency Bands

- **Delta (δ)**: 0.5–4 Hz — deep sleep, slow-wave activity
- **Theta (θ)**: 4–8 Hz — drowsiness, memory processing, meditation
- **Alpha (α)**: 8–13 Hz — relaxed wakefulness, eyes closed, occipital rhythms
- **Beta (β)**: 13–30 Hz — active thinking, motor control, alertness
  - Low beta: 13–20 Hz
  - High beta: 20–30 Hz
- **Gamma (γ)**: 30–100+ Hz — sensory binding, cognitive processing
  - Low gamma: 30–60 Hz
  - High gamma: 60–100+ Hz
- **High-frequency oscillations (HFO)**: >100 Hz — sometimes studied in epilepsy research
