## AI-diagnoser
*Intelligent Diagnostic Support System*

## Overview

The AI Diagnoser is a smart, AI-powered medical assistant designed to support healthcare professionals in diagnosing patients efficiently and accurately. This system reduces human diagnostic errors by analyzing vitals, symptoms, test results, and patient history to suggest diagnoses, tests, and treatments.

*`Note: This project is currently in the theoretical and planning phase, with the full proposal included. The AI modeling and data processing are ongoing.`*

## Key Features

- Automatic Reading of Vitals: Data is collected directly from hospital devices (connected via pins) – no manual entry required.
- Symptom Analysis: Doctor inputs patient symptoms.
- Initial Diagnosis: Generated based on vitals and symptoms.
- Test Recommendations: The model suggests relevant tests.
- Final Diagnosis: Updated based on test results.
- Prescriptions & Procedures: The model recommends treatment and prescriptions.

## Architecture (Planned)

- Frontend: Mobile application for healthcare professionals
- Backend: Flask API with endpoints for input, processing, and output
- Model: ML-based diagnostic model trained on medical datasets

## Datasets Used

The project uses anonymized healthcare datasets with over 400,000 records, including:

- Vitals
- Labevents
- Diagnoses (ICD-coded)
- Prescriptions & Drugs
- Doctor Notes
- Microbiology Events
- Procedures & ICD Procedures

A reduced sample (20,000 records) is used for initial prototyping due to computational constraints.

## Proposal

The full proposal outlining problem definition, SDG linkage, methodology, workflow, data sources, and expected impact is included as proposal.pdf in the root of this repository.

## Future Plans

- Complete data preprocessing and cleaning
- Develop and train diagnostic model
- Implement Flask backend
- Launch prototype on mobile app

## Contributions

Contributions are welcome! If you're a data scientist, medical expert, or developer interested in working on this meaningful project, feel free to reach out or open an issue.

## License

This project is distributed under a custom restrictive license.  
Please refer to the `LICENSE` file for detailed terms and conditions regarding usage, copying, and distribution.
