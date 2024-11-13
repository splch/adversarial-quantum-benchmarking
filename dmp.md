# Data Management Plan

## 1. Project Overview

This project focuses on developing adversarial quantum circuits using permuted mirror circuits, maximally entangled circuits, and other circuits to create worst-case-scenario benchmarks for quantum computers. The aim is to design circuits that can accurately estimate the quality of a quantum computer without the scalability issues of Quantum Volume or the non-repeatability of Randomized Benchmarking.

## 2. Data Description

### Types of Data Generated:

- **Quantum Circuit Designs**: Schematics and parameters of adversarial quantum circuits.
- **Raw Execution Data**: Measurement outcomes from running the circuits on various quantum hardware platforms.
- **Processed Data**: Statistical analyses, performance metrics, benchmarking results, and comparisons to reported Quantum Volume metrics.
- **Software Code**: Python scripts and Jupyter notebooks used for circuit design, optimization, and data analysis.

## 3. Data Storage and Preservation

### During the Project:

- Data will be stored securely in this GitHub repository and on secure institutional servers with regular backups.
- Version control will be managed using Git for code and scripts.

### Long-term Preservation:

- Upon project completion, datasets will be archived in publicly accessible repositories such as Zenodo or the DOE Data Explorer.
- The GitHub repository will remain public for ongoing access and collaboration.

## 4. Data Standards and Metadata

### Data Formats:

- **Circuit Designs**: Stored in OpenQASM (.qasm) format.
- **Raw and Processed Data**: Saved in CSV (.csv) formats.
- **Code and Scripts**: Provided as Python (.py) files and Jupyter notebooks (.ipynb).

### Metadata:

- Each dataset will include a README file with:

  - **Description**: Summary of the data and its purpose.
  - **Methodology**: Details on data collection methods and hardware used.
  - **Provenance**: Information on data origin, version, and authorship.
  - **Software Dependencies**: Versions of software libraries and tools used.

## 5. Data Sharing and Accessibility

### Sharing Plans:

- All data and code will be made openly available under the MIT License.
- Datasets and metadata will be accessible through this GitHub repository and linked open-access repositories.

### Access Policies:

- No restrictions or embargo periods; data will be available upon publication.
- Users are free to use, modify, and distribute the data with appropriate citation.

## 6. Ethical and Legal Compliance

- **Privacy and Confidentiality**: No personal or sensitive data is involved.
- **Intellectual Property Rights**: All project outputs are intended for open dissemination.
- **Export Control Compliance**: All materials comply with U.S. export control laws.

## 7. Roles and Responsibilities

- **Data Management Lead**: Spencer Churchill (contact: [spence@duck.com])
  - Responsible for data collection, storage, documentation, and sharing.
- **Contributors**: Listed in the CONTRIBUTORS.md file.

## 8. Resources and Budget

- Data management activities are integrated into the project's workflow.
- No additional funding is required beyond existing project resources.

## 9. Data Quality and Validation

- **Validation Methods**:

  - Reproducibility checks through repeated circuit executions.
  - Cross-platform comparisons to ensure consistency across different hardware.
  - Peer review through publication and community feedback.

## 10. Documentation and Reporting

- Regular updates and documentation will be provided in the GitHub repository.
- Issues and enhancements tracked via the repository's issue tracker.

## 11. Compliance with DOE Requirements

- The data management practices align with the DOE's guidelines for digital research data.
- The project supports the DOE's mission to advance scientific understanding and innovation.

## 12. Future Work and Sustainability

- Encourage community contributions and collaboration.
- Plan for ongoing maintenance of the repository and datasets.

---

*This Data Management Plan outlines our commitment to responsible data handling, ensuring that our research outputs are accessible, reusable, and valuable to the wider scientific community.*
