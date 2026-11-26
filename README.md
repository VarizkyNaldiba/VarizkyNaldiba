# Varizky Naldiba Rimra

Applied Machine Learning and IoT Systems Engineer based in Malang, Indonesia. Final-year Informatics Engineering student at Politeknik Negeri Malang (2022–Present).

I design and build resilient, end-to-end data pipelines: from edge hardware and non-linear sensor calibration curves (ESP32/C++) to applied deep learning models (Computer Vision, LSTM) and cloud-connected spatial platforms.

[![Portfolio Website](https://img.shields.io/badge/Production_Site-varizkynaldiba.vercel.app-0f172a?style=flat-square&logo=vercel&logoColor=white)](https://varizkynaldiba.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-VarizkyNaldiba-0f172a?style=flat-square&logo=github&logoColor=white)](https://github.com/VarizkyNaldiba)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Varizky_Naldiba-0f172a?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/varizkynaldiba/)
[![Email](https://img.shields.io/badge/Email-varizkynr%40gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=white)](mailto:varizkynr@gmail.com)

---

## Verified Honors & Competitions

| Recognition | Organization / Contest | Validated Project Scope | Year |
| :--- | :--- | :--- | :---: |
| **Juara Harapan 2 (2nd Runner Up)** | LKTI Nasional Techno Fair & Seminar (TFS) 2026<br/>*SK Direktur Polinema No. 27881/PL2.3/KM/2026* | **CatfishCare**: Autonomous freshwater telemetry and closed-loop aeration control. | 2026 |
| **Incentive Grant Phase 2 Recipient** | PKM POLINEMA 2026<br/>*SK No. 40/WADIR.III/KM/2026* | **Smart Aquaculture Intelligence System (SAIS)**: Digital twin modeling and distributed telemetry network. | 2026 |
| **Rank 18 of 82 National Teams** | Intelecta Cup 2025 Data Competition<br/>*Kaggle Final Metric: 94.310* | **Agroclimatology ML**: Multivariate climatic regression predicting anomalous weather indices. | 2025 |
| **National Finalist** | LKTI Nasional Techno Fair & Seminar (TFS) 2025<br/>*SK No. 16002/PL2.3/KM/2025* | **AlgaSense**: Marine telemetry and LSTM harvest forecasting in Sumenep, Madura. | 2025 |
| **Official Participant** | Hology 8.0 National Data Mining Competition | **Crowd Density Estimation**: Multi-column convolutional neural regression (MCNN/CSRNet). | 2025 |
| **Official Participant** | Jatim Datathon 2025 (Diskominfo Jawa Timur) | **SLB Accessibility Analysis**: Spatial disparity evaluation across 38 East Java regencies. | 2025 |

---

## Engineered Projects

### 1. IoT, Sensor Telemetry & Hardware Systems

* **Aquavion — IoT Aquaculture Telemetry Platform**
  * *Architecture:* Microcontroller-to-cloud telemetry tracking pH, DS18B20 temperature, and nephelometric turbidity for freshwater catfish ponds.
  * *Engineering Highlight:* Developed polynomial calibration offset curves and a non-volatile circular flash ring buffer on the ESP32, preventing data loss during remote connectivity dropouts.
  * *Stack:* Next.js, Firebase Realtime Database, ESP32, Arduino C++
  * *Links:* [Live Dashboard](https://aqua-vion.vercel.app/) · [Firmware Repository](https://github.com/VarizkyNaldiba/Smart_Aqua_IOT) · [Technical Roadmap](https://dashboard-notion-aqua-vion.vercel.app/)

* **CatfishCare — Automated Aquaculture Care System**
  * *Architecture:* Closed-loop actuation system pairing physical optocoupler relays with submerged chemical sensors for real-time pond water treatment.
  * *Engineering Highlight:* Enforced threshold-driven automatic water replenishment and aeration routines without cloud dependency.
  * *Stack:* ESP32, C++, Sensor Probes, Relays, Control Loop
  * *Links:* [Firmware Repository](https://github.com/VarizkyNaldiba/Smart_Aqua_IOT) · [Live Dashboard](https://aqua-vion.vercel.app/)

* **Smart Aquaculture Intelligence System (SAIS)**
  * *Architecture:* Digital twin framework and simulation model forecasting aquatic ecosystem parameters for commercial aquaculture.
  * *Engineering Highlight:* Selected for the Phase 2 Incentive Grant under Polinema internal review.
  * *Stack:* Digital Twin Modeling, AI Architecture, Autonomous IoT Network
  * *Links:* [Project Overview](https://varizkynaldiba.vercel.app/#projects)

* **AlgaSense — Marine Seaweed Aquaculture IoT & ML**
  * *Architecture:* Marine buoy telemetry coupled with recurrent neural networks for harvest timeline prediction.
  * *Engineering Highlight:* Trained LSTM networks over noisy marine time-series (salinity, pH, dissolved oxygen) filtered through sliding temporal windows.
  * *Stack:* Python, TensorFlow, Keras LSTM, ESP32, Waterproof Probes
  * *Links:* [Source Code](https://github.com/VarizkyNaldiba/Algasense)

---

### 2. Machine Learning, Computer Vision & Analytics

* **Multi-Column Crowd Density Estimation**
  * *Architecture:* Deep convolutional regression network resolving perspective distortion in high-density surveillance feeds.
  * *Engineering Highlight:* Constructed parallel multi-scale receptive filter heads (3x3, 5x5, 7x7) based on MCNN and CSRNet architectures.
  * *Stack:* Python, PyTorch, TensorFlow, OpenCV
  * *Links:* [Source Code](https://github.com/VarizkyNaldiba/PenyelamHandal_Hology)

* **Agroclimatology Time-Series Weather Forecasting**
  * *Architecture:* Multivariate regression pipeline forecasting regional climatic anomalies. Ranked 18/82 nationally with a Kaggle score of 94.310.
  * *Engineering Highlight:* Engineered lag transformation matrices and trained gradient-boosted ensembles (CatBoost/XGBoost) with blocked cross-validation.
  * *Stack:* Python, CatBoost, XGBoost, Scikit-Learn, Pandas
  * *Links:* [Project Summary](https://varizkynaldiba.vercel.app/#projects)

* **Fruit Variety Classification Pipeline**
  * *Architecture:* Classical computer vision pipeline categorizing 16 fruit species under non-uniform illumination.
  * *Engineering Highlight:* Combined Gray-Level Co-occurrence Matrix (GLCM), 2D Wavelet decomposition, and HOG gradient features fed into tuned Support Vector Machines.
  * *Stack:* Python, OpenCV, Scikit-Learn, GLCM, Wavelet 2D, SVM
  * *Links:* [HuggingFace Space](https://huggingface.co/spaces/Zelectra/PBL.MachineLearningAndPCVK)

* **AI Restaurant Advisory System**
  * *Architecture:* Deterministic decision-support application analyzing dish profit margins and ingredient volatility for food businesses.
  * *Engineering Highlight:* Structured prompt schema enforcing mathematical calculations and Boston Consulting Group (BCG) portfolio matrices.
  * *Stack:* Python, Google Gemini API, Streamlit
  * *Links:* [Live Application](https://varizkynaldiba-project-of-llm-based-tools-and-gem-fnb-rm-vjbmhr.streamlit.app/)

---

### 3. Geospatial Platforms & Full-Stack Systems

* **SIMOJANG Brantas — Participatory Flood WebGIS**
  * *Architecture:* Production hydrological risk WebGIS for the Upper Brantas River Basin in research collaboration with BRIN.
  * *Engineering Highlight:* Built GPS-geofenced crowdsourcing workflows and optimized GeoJSON polygon rendering for high-frequency map updates.
  * *Stack:* Leaflet, GeoJSON, OpenStreetMap, Spatial DB
  * *Links:* [Live System](https://simojang.let.polinema.ac.id/)

* **Special Education School (SLB) Spatial Disparity Analysis**
  * *Architecture:* Regional spatial disparity index quantifying educational infrastructure access across 38 East Java regencies.
  * *Engineering Highlight:* Implemented Levenshtein distance string matching to harmonize inconsistent administrative registries directly to geospatial polygon coordinates.
  * *Stack:* Python, Pandas, GeoJSON, Folium GIS
  * *Links:* [HuggingFace Space](https://huggingface.co/spaces/Tim-Maju-Lancar-Datathon/Dashboard-Tim-Maju-Lancar-Datathon-Jatim-2025)

* **East Java Secondary School Spatial Distribution**
  * *Architecture:* Point pattern clustering mapping secondary school coverage radii across urban and rural districts.
  * *Engineering Highlight:* Used K-Means spatial clustering and buffer distance calculations to identify educational desert zones.
  * *Stack:* Python, Folium, GeoJSON, Pandas, K-Means
  * *Links:* [Source Code](https://github.com/VarizkyNaldiba/SchoolSpatial_on_EastJava)

* **SIMPRES — Student Achievement Management Portal**
  * *Architecture:* Departmental portal managing verified academic accomplishments, faculty endorsement workflows, and competition candidate selection.
  * *Engineering Highlight:* Embedded PROMETHEE II multi-criteria algorithm to match verified student competencies against competition profiles.
  * *Stack:* Laravel, PHP, MySQL, PROMETHEE DSS, RBAC
  * *Links:* [Source Code](https://github.com/VarizkyNaldiba/Prestasi-Mahasiswa-S4)

* **Sistem Tata Tertib Mahasiswa**
  * *Architecture:* Campus compliance management platform digitizing disciplinary tracking and student appeals.
  * *Engineering Highlight:* Replaced paper notices with an audit-logged workflow designed from interactive Figma prototypes.
  * *Stack:* Laravel, PHP, MySQL, Bootstrap, Figma
  * *Links:* [Source Code](https://github.com/VarizkyNaldiba/TataTertibMhs)

---

## Technical Skills

* **Core Languages:** Python, C/C++, JavaScript, PHP, SQL, HTML5, CSS3, R
* **Machine Learning & AI:** TensorFlow, PyTorch, Keras, OpenCV, Scikit-Learn, LSTM, CNNs (MCNN, CSRNet), Google Gemini API
* **Data Science & Geospatial:** Pandas, NumPy, Matplotlib, Seaborn, Folium GIS, QGIS, GeoJSON, Spatial Regression
* **IoT & Embedded Systems:** ESP32, Arduino, Analog/Nephelometric Probes, Non-Linear Sensor Calibration, Flash Ring Buffering
* **Web & Systems:** Next.js, React, Laravel, Streamlit, Firebase Realtime Database, MySQL, PostgreSQL, REST APIs
* **Tools & Platforms:** Git, GitHub, Linux, VS Code, Google Colab, HuggingFace, Figma

---

## Production Portfolio

Full case studies, live telemetry visualizers, and interactive demos are accessible on my primary website:  
**[https://varizkynaldiba.vercel.app/](https://varizkynaldiba.vercel.app/)**
