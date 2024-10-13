This project focuses on EEG data analysis, specifically detecting and analyzing event-related potentials (P300) using Python, MNE, and PCA. Key steps include:

- Data Preprocessing: Load and preprocess EEG data from CSV, creating an MNE RawArray object and extracting relevant channels.
- Event Detection: Identify target and non-target events in the signal for analysis.
- Dimensionality Reduction: Apply PCA to reduce the EEG data from 3 channels to 1 per trial.
- Time-Frequency Analysis: Perform time-frequency analysis using custom DFT and generate spectrograms for visualization.
- Phase Consistency: Calculate inter-trial phase consistency to measure signal stability across trials.
