# AutoMicrobe-AST-Vision 🧫🔬

An open-source computer vision and deep learning toolkit designed for **Clinical Microbiology** and **Chemical Pathology** laboratories. Built to run on standard smartphone images of agar plates and microscopy fields in low-resource settings.

### 🎯 Core Diagnostic Modules
* **Module 1 — Automated Colony Counter (CFU/mL):** Uses OpenCV adaptive thresholding and marker-based watershed segmentation to separate clumped colonies and compute viable counts.
* **Module 2 — Kirby-Bauer Antibiogram Reader (AST):** Calibrates pixel-to-millimeter scale using standard **6 mm** antibiotic disks (`cv2.HoughCircles`), measures inhibition zone diameters in **mm**, and maps results to **CLSI / EUCAST** Susceptible (S), Intermediate (I), and Resistant (R) breakpoints.
* **Module 3 — Pathogen Morphology & Chromogenic Classifier:** Deep learning classification (YOLOv8 / PyTorch) for Gram-stain smears and differential media (Blood Agar hemolysis, MacConkey lactose fermentation).

---

### 🗺️ Development Roadmap
- [x] Repository architecture & clinical workflow specification
- [ ] **v1.0:** OpenCV 6 mm disk calibration + inhibition zone millimeter calculator (`01_AST_Zone_Measurement.ipynb`)
- [ ] **v1.1:** Watershed bacterial colony counter & CFU/mL dilution calculator (`02_Colony_Counter_Watershed.ipynb`)
- [ ] **v1.2:** CLSI/EUCAST automated breakpoint lookup + ESBL / D-test synergy alerts
- [ ] **v2.0:** Interactive Streamlit / Gradio mobile web interface

---

### 🛠️ Tech Stack
`Python` • `OpenCV` • `Scikit-Image` • `PyTorch` • `YOLOv8` • `Pandas` • `Google Colab`

---

### 👤 Author
**Mbuh Harmony Neba** — Biotechnologist & Computational Biologist | BSc Biochemistry (University of Buea) | Molecular & Veterinary Research Intern @ LANAVET  
🔗 [Connect on LinkedIn](https://www.linkedin.com/in/mbuh-harmony-neba-906215314?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
