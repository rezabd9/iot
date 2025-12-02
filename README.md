# A Quantitative Framework for Integrated Safety and Security Co-Analysis in IoT-Based Smart Systems: Toward Unified Modelling of Safety and Security

This repository contains code, models, data, and documentation for IoT sensor systems developed as part of PhD research at the University of Bradford, UK. The project focuses on quantitative risk assessment, fault tree analysis, attack tree modeling, and integrated safety-security frameworks (e.g., using the CIAS model) for cyber-physical systems like smart water treatment facilities and remote monitoring sensors.

## Project Overview
- **Objective**: Develop a unified modeling approach for safety and security co-analysis in IoT ecosystems, enabling quantitative evaluation of vulnerabilities, threats, and risks.
- **Key Components**:
  - IoT sensor integrations (e.g., Arduino-based gas and sonar sensors).
  - Attack tree and fault tree diagrams.
  - Risk quantification tools using CVSS, EPSS, and probabilistic models.
  - Case studies on safety-security interactions in smart systems.
- **Technologies**: Arduino, LaTeX/Overleaf for documentation, Python for analysis (if applicable), and academic citation tools like Scopus.

For detailed methodology, refer to the dissertation chapters in `/docs` or contact the author.

## Installation and Setup
1. Clone the repository: `git clone https://github.com/yourusername/your-repo-name.git`
2. Install dependencies (e.g., for Arduino sketches): Ensure Arduino IDE is installed and libraries like NewPing for sonar are added.
3. For analysis scripts: Run `pip install -r requirements.txt` if Python tools are included.
4. Build documentation: Use Overleaf or `pdflatex` for LaTeX files in `/docs`.

## Usage
- **Running Simulations**: Execute Arduino sketches in `/src/arduino` for sensor testing.
- **Generating Models**: Use tools in `/models` to create attack trees or fault trees (e.g., via Python or draw.io exports).
- **Non-Commercial Use Only**: This project is for academic and research purposes. See License section below.

Example: To simulate a smart temperature sensor system, upload `sensor_sketch.ino` to your Arduino board and monitor via serial output.

## Contributing
Contributions are welcome for research reproducibility. Please fork the repo, create a branch, and submit a pull request with changes to models or documentation. Cite the project in your work.

## License
This project is licensed under a non-commercial use agreement. You may use, study, modify, and share the materials for non-commercial, educational, or research purposes only. Commercial use, distribution, or reproduction requires explicit written permission from the copyright holder.

Copyright © Mohammadrezaul Karim  
Email: [mrkarim2@bradford.ac.uk](mailto:mrkarim2@bradford.ac.uk)  
Affiliation: PhD Research, University of Bradford, UK  

For full terms, see `/LICENSE` (or create one based on this notice). No warranties are provided.

## Acknowledgments
- Supervised under the University of Bradford's IoT Systems Security program.
- Built on open-source tools like Arduino and academic frameworks for fault/attack tree analysis.
- Feedback from advisors on dissertation revisions is incorporated.

## Contact
For questions, collaborations, or permissions, email [mrkarim2@bradford.ac.uk](mailto:mrkarim2@bradford.ac.uk).
