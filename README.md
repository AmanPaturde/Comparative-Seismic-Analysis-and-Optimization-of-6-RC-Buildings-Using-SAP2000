# Comparative Seismic Analysis and Optimization of 6 RC Buildings Using SAP2000
### Response Spectrum Analysis in SAP2000 | IS 1893 (Part 1): 2016

## Project Summary
Comparative seismic analysis of 6 RC building models (G+5 to G+20, regular and vertically irregular) using the Response Spectrum Method as per IS 1893:2016 in SAP2000 v25.

**Key Question:** How do building height, vertical irregularity, and shear walls affect seismic response?

---

## Models Analyzed
| Model | Configuration | Height |
|---|---|---|
| 1 | G+5 Regular Bare Frame | 18 m |
| 2 | G+10 Regular Bare Frame | 33 m |
| 3 | G+15 Regular Bare Frame | 48 m |
| 4 | G+20 Regular Bare Frame | 63 m |
| 5 | G+20 Vertically Irregular (Setback at 11F) | 63 m |
| 6 | G+20 Irregular + Central RC Shear Wall Core | 63 m |

---

## Key Results

| Parameter | G+5 | G+20 Regular | G+20 Irregular | G+20 + Shear Wall |
|---|---|---|---|---|
| Time Period (s) | 0.831 | 3.121 | 2.313 | 1.951 |
| Base Shear (kN) | 236.5 | 239.1 | 315.8 | 577.4 |
| Max Drift (mm) | 1.365 | 1.400 | 1.631 | 1.406 |

---

## Key Engineering Findings
1. Time period increases consistently with building height (0.831s → 3.121s)
2. Base shear is NOT linearly proportional to height — peaked at G+10 (282.4 kN)
3. Vertical irregularity increased base shear by 32% vs regular G+20
4. Central shear wall core reduced maximum drift by **13.8%** (DREI = 13.8%)
5. Drift Concentration Factor (DCF) of optimized model = 2.15
6. Lower base shear does NOT imply safer structural performance

---

## Tools & Standards
- **Software:** SAP2000 v25
- **Analysis Method:** Response Spectrum Analysis (CQC combination)
- **Codes:** IS 1893:2016, IS 456:2000, IS 875 Part 2, IS 13920

---

## Seismic Parameters Used
- Zone III | Z = 0.16 | I = 1.0 | R = 5 (SMRF)
- Medium Soil (Type II) | Damping = 5%

---

## Files in This Repository
- `/Report` [Seismic Analysis of Regular and Irregular RC Buildings by Aman Paturde.pdf](https://github.com/user-attachments/files/28188856/Seismic.Analysis.of.Regular.and.Irregular.RC.Buildings.by.Aman.Paturde.pdf)
  
- `/Model Screenshots`
   
<img width="1333" height="2000" alt="Image" src="https://github.com/user-attachments/assets/53b679eb-21d0-4f84-a060-86ac352bfdf2" /> 

- `/Results`
   
- `/Drift Profiles`
  
<img width="1196" height="777" alt="Image" src="https://github.com/user-attachments/assets/3f2763ec-56cf-4d0b-9cf2-38e46b301e29" />
<img width="1189" height="789" alt="Image" src="https://github.com/user-attachments/assets/3633926e-5737-480b-99da-424b7b795ea1" />
<img width="1193" height="771" alt="Image" src="https://github.com/user-attachments/assets/c28f805a-d803-47b1-b9ea-11ed44ea7e5d" />
<img width="1188" height="768" alt="Image" src="https://github.com/user-attachments/assets/fab5be1d-09bd-4cf9-aeb3-dd11a0fff1f4" />
<img width="1197" height="778" alt="Image" src="https://github.com/user-attachments/assets/c6a34c89-f301-4edc-9c51-82aaf3d3b58a" />
<img width="1193" height="780" alt="Image" src="https://github.com/user-attachments/assets/e674e10f-96f2-4bc6-9cdd-b60a05d64068" />

- `/Comparative Graphs` 

<img width="1202" height="791" alt="Image" src="https://github.com/user-attachments/assets/6db5af1a-e904-445d-8abc-8ccb05ff374e" />
<img width="1188" height="786" alt="Image" src="https://github.com/user-attachments/assets/33e851c3-4101-4249-8867-e9b8861c235c" />
<img width="1187" height="775" alt="Image" src="https://github.com/user-attachments/assets/43464887-a9d1-4bad-823b-12ce5d79923e" />
<img width="1199" height="779" alt="Image" src="https://github.com/user-attachments/assets/9189e637-9a30-4732-8ce0-4a1a2db3b39e" />
<img width="1197" height="776" alt="Image" src="https://github.com/user-attachments/assets/cc480465-be75-480d-acff-e8618ab7a62e" />
<img width="1194" height="767" alt="Image" src="https://github.com/user-attachments/assets/20ec6b34-16a3-4eba-ac53-6b55a18a4088" />
