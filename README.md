# Medical Engineering Portfolio

<table>
  <tr>
    <td><b>License</b></td>
    <td><code>MIT</code></td>
  </tr>
</table>

Archive of independent research and engineering workflows in computational design and simulation, biomechanics, and medical data coding.

**Contact:** [LinkedIn](https://www.linkedin.com/in/naima-yusuf-6699452b6/)

## Technical Competencies
- **CAD and Prototyping**: Autodesk Fusion 360 · Electromechanical Prototyping · 3D Printing
- **Engineering and Electronics**: Applied Mechanics · Circuit Design · Engineering Calculus · Statistical and Data Analysis
- **Programming and Data**: Python · MATLAB · Medical Image Processing (CT/MRI)
- **Web and Methodology**: HTML · CSS · Basic JavaScript (Debugging) · Agile / Scrum Design Frameworks

## Engineering Projects

### Tendon-Driven Robotic Hand

> [!WARNING]
> Active development: Physical testing and code updating.

3D printed robotic hand, utilising a **servo-actuated tendon mechanism**, currently driven by a potentiometer loop with an **active scalability pipeline** for **Surface Electromyography muscle-sensor integration**

- 📐 **Design & Prototyping:** Cardboard prototyping, Autodesk Fusion 360, circuit fabrication, 3D printing
- 🧪 **Testing Methods:** Kinematic **range-of-motion tracking**, tendon tension profiling, and **iterative** fit tolerance validation.
- 🌐 **Links:** [Design Progress Log](https://ny262.github.io/Tendon-Driven-Robotic-Hand/) | [CAD & Data Repository](https://github.com/ny262/Tendon-Driven-Robotic-Hand)

---

### Paediatric Femur Plate Simulation

> [!WARNING]
> Active development: Core simulations and parameters updating.

An **anatomically conscious**, highly adaptable, **patient-specific** femoral plate, engineered to work in tandem with the human body's natural healing mechanisms.

- 📐 **Design:** Autodesk Fusion 360
- 🧪 **Testing Methods:** FEA verification of **Ti-6Al-4V** vs. **cortical bone limits** under gait simulation.
- 🌐 **Links:** [Design Progress Log](https://ny262.github.io/Paediatric-Femur-Plate-Simulation/) | [CAD & Data Repository](https://github.com/ny262/Paediatric-Femur-Plate-Simulation)

---

### NHS Prescription-Deprivation Analysis

<table>
  <tr>
    <td><b>Python</b></td>
    <td><code>3.10+</code></td>
  </tr>
</table>

> [!WARNING]
> Raw datasets are omitted due to scale. To run this pipeline, download the official sources listed below into your local directory and execute.

Deployed an optimised python pipeline to explore the disparities in GLP-1 prescriptions across socio-economic boundaries. 

- 🧮 **Key Pipeline Metrics**:
  - Total frequency of glp-1 prescription record counts across NHS England.
  - Matches each GP to its primary patient catchment area to map prescription density to the LSOA
  - Correlates the LSOA against IMD Deciles (1–10)

- 📂 **Data Sources:**
  - [NHSBSA October 2025 EPD Registry](https://opendata.nhsbsa.net/dataset/english-prescribing-dataset-epd-with-snomed-code/resource/d28455b2-7373-4d4a-8577-b28973ddba00).
  - *Reference Directories (GP, LSOA, & IMD Ranks):* Filtered and pre-loaded directly within the [/reference_data](https://github.com/ny262/NHS-Prescription-Deprivation-Analysis/tree/main/reference_data) directory of this repository for convenience (**gp_practice_lsoa_map.csv** and **lsoa_deprivation_index.csv**).

- 🌐 **Links:** [Analysis Results](https://ny262.github.io/NHS-Prescription-Deprivation-Analysis/) **|** [Data Repository](https://github.com/ny262/NHS-Prescription-Deprivation-Analysis)
