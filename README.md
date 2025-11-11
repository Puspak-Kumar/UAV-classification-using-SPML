# UAV-classification-using-SPML
Advanced radar-based classification system for detecting and distinguishing UAVs, birds, and RC aircraft using SVMD signal decomposition and deep learning feature extraction

✅ Project Direction 

our system will:

A. Collect / Use radar time-series echo returns

B. Decompose signal using one or more of:

  1. STFT

  2. EMD (Empirical Mode Decomposition)

  3. Wavelet Packet Decomposition

  4. Hilbert Transform

C. Extract micro-Doppler & temporal features

D.Train a classifier to distinguish:

    1.UAV (quadrotor or small drone)

    2.Birds

    3.RC Aircraft

✅ Key Reason Why Time-Series Works

Bird wings,
Drone propellers,
RC aircraft rigid-body motion
→ All create different micro-Doppler signatures and periodic motions.

So classification is absolutely possible using only time-domain signals.

📅 Project Execution Timeline (We will follow this)
Phase	Task	Deliverables.

Phase 1 	Literature Study + Dataset Search	6-page review + reference papers.

Phase 2 	Signal Decomposition & Feature Extraction	Python/Matlab feature extraction scripts.

Phase 3 	Model Training (SVM / CNN / LSTM)	Classification code, plots, accuracy table.

Phase 4 	Result Analysis	Confusion matrix + explanation.

Phase 5 	Documentation + PPT + Viva Prep	Final report + PPT + answers.
