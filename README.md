# qPCR Reagent Volume Calculator

A web-based calculator designed to assist with the preparation of reagent volumes for qPCR experiments, including Master Mix preparation, TaqMan Assay volumes, DNA input, safety margins, and 96-well plate mapping.

## 🧬 About the Project

The **qPCR Reagent Volume Calculator** is an educational and laboratory support tool developed to facilitate the planning and preparation of qPCR reactions.

The calculator allows users to estimate the required volume of each reagent based on the number of biological samples, technical replicates, controls, reaction volume, assay concentration, DNA concentration, target DNA mass, and an additional safety margin.

The tool also provides a visual representation of a 96-well plate, allowing users to identify and organize samples and controls before performing the experiment.

## 🔬 Main Features

* Calculation of the total number of reactions
* Technical replicate management
* Inclusion of positive and negative controls
* Configurable reaction volume
* Configurable TaqMan Assay concentration
* DNA volume calculation based on target DNA mass and stock concentration
* Automatic calculation of sterile water volume
* Adjustable safety margin
* Calculation of total reagent volumes required
* Interactive 96-well plate mapping
* Sample and control identification by well
* Step-by-step explanation of reagent calculations
* Export of results as PNG
* Export of results as PDF
* Automatic experiment metadata display
* Responsive web interface

## 🧪 Calculation Overview

The calculator uses the following general relationships:

### Total number of wells

The total number of reactions is calculated as:

**N = samples × replicates + controls**

### Safety-adjusted number of reactions

A configurable safety margin is applied to compensate for potential preparation and pipetting losses:

**Nₛₐfₑₜᵧ = N × (1 + safety margin)**

### DNA volume

The required DNA volume is calculated from the target DNA mass and stock concentration:

**Vᴅɴᴀ = target DNA mass / DNA stock concentration**

### Master Mix volume

For a 2X Master Mix:

**Vᴍᴍ = total reaction volume / 2**

### TaqMan Assay volume

The Assay volume is calculated according to the selected stock concentration:

**Vᴀssᴀʏ = total reaction volume / assay concentration**

### Sterile water volume

The water volume is calculated from the remaining reaction volume:

**Vʜ₂O = total reaction volume − fixed component volumes**

The total reagent requirements are then calculated using the safety-adjusted number of reactions.

## 💻 Technologies

This project was developed using:

* HTML5
* CSS3
* JavaScript
* Tailwind CSS
* html2canvas
* jsPDF

The application runs directly in a modern web browser and does not require installation.

## 🚀 How to Use

### Option 1 — Run locally

Download or clone this repository and open:

```text
index.html
```

in a modern web browser.

No installation or server is required for basic use.

### Option 2 — Use the online version

If GitHub Pages is enabled for this repository, the calculator can be accessed directly through a web browser without downloading the project.

## 📊 Workflow

1. Enter the experiment information.
2. Enter the number of biological samples.
3. Define the number of technical replicates.
4. Add the number of controls.
5. Configure the reaction volume.
6. Select the TaqMan Assay concentration.
7. Enter the target DNA mass.
8. Enter the DNA stock concentration.
9. Define the desired safety margin.
10. Review the calculated reagent volumes.
11. Optionally map samples and controls to the 96-well plate.
12. Export the final calculation as PNG or PDF.

## ⚠️ Important Notice

This calculator is intended as a **laboratory planning and educational support tool**.

Users are responsible for verifying all calculated volumes and experimental parameters against the protocols, instructions, reagent specifications, and recommendations provided by the respective manufacturers and their laboratory's validated procedures.

The calculator does not replace laboratory protocols, institutional procedures, professional supervision, or experimental validation.

## 🎓 Educational Use

This project was developed with the aim of supporting laboratory education, molecular biology training, and practical activities involving qPCR planning.

It may be used in:

* Universities
* Research laboratories
* Teaching laboratories
* Molecular biology courses
* Practical training
* Educational workshops
* Science communication activities

## 👨‍🔬 Author

**Juan Carlos Ramos de Oliveira**

MSc Student in General and Applied Biology
Institute of Biosciences – São Paulo State University (IBB/UNESP), Botucatu, Brazil

## 🧑‍🔬 Academic Advisor

**Ariane Leite Rozza**

Institute of Biosciences – São Paulo State University (IBB/UNESP), Botucatu, Brazil

## 🏛️ Institutional Context

The project was developed in the context of laboratory and scientific activities associated with the **Experimental Research Unit (UNIPEX)**.

## 📅 Version

**Version 1.0**

Initial release: **2025**

## 📄 License

This project is distributed under a **Non-Commercial Educational License**.

It may be freely used, copied, and adapted for educational, academic, research, and non-commercial laboratory purposes, provided that the original author and project are appropriately credited.

Commercial use, sale, redistribution as a commercial product, or incorporation into a commercial service requires prior written permission from the author.

See the `LICENSE` file for the complete terms.

## 📚 Citation

If you use this software in an academic, educational, research, or science communication activity, please cite:

> Oliveira, J. C. R. *qPCR Reagent Volume Calculator*. São Paulo State University (UNESP), Institute of Biosciences, 2025.

Please also provide the URL of this GitHub repository when possible.

## 🤝 Acknowledgments

The author acknowledges **Ariane Leite Rozza** for academic guidance and the **Institute of Biosciences of São Paulo State University (IBB/UNESP)** for the academic and research environment associated with the development of this project.

## 📬 Contact

**Juan Carlos Ramos de Oliveira**
Email: [juan.oliveira@unesp.br](mailto:juan.oliveira@unesp.br)
