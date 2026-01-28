# Complete 14-Week Course Outline

## Course Structure
- **Total Weeks:** 14
- **Total Classes:** 28 (2 per week)
- **Class Format:** 30-40 min lecture + 80-90 min hands-on lab
- **Student Groups:** 5-7 groups of 3-4 students each

---

## Phase 1: Foundations (Weeks 1-4)

### Week 1: Introduction to ML & Mathematical Encoding

**Class 1: Introduction to Machine Learning**
- *Lecture Topics:*
  - Why ML in medicine? (Classical physics vs. medical complexity)
  - From ELIZA to modern AI (rule-based → data-driven)
  - The ML Pipeline: Data Collection → Feature Design → Training → Testing
  - Deep dive into each pipeline step
  - The curse of dimensionality
  - ML taxonomy (supervised, unsupervised, reinforcement)
- *Lab:* Python basics, NumPy, pandas with Pima diabetes dataset (768 patients)
- *Reading:* Textbook Chapter 1

**Class 2: Mathematical Encoding of Medical Data**
- *Lecture Topics:*
  - Why mathematical encoding?
  - Type 1: Numerical data (vitals, lab results)
  - Type 2: Categorical data (one-hot encoding)
  - Type 3: Imaging data (grayscale, RGB, 3D medical imaging)
  - Type 4: Time-series data (ECG, EEG)
  - Type 5: Text data (clinical notes, NLP)
  - Type 6: Genomics data (DNA, RNA encoding)
  - PyTorch tensors: shapes, operations, GPU acceleration
- *Lab:* Tensor operations, encoding medical data types
- *Reading:* Textbook Chapter 2

### Week 2: Python Fundamentals for ML

**Class 3: Python, NumPy & pandas**
- *Lecture Topics:*
  - Python data structures
  - NumPy arrays and operations
  - pandas DataFrames for medical data
  - Data cleaning and preprocessing
  - Exploratory data analysis (EDA)
- *Lab:* Real medical dataset exploration, missing data handling
- *Reading:* Python for Data Analysis (McKinney)

**Class 4: Data Visualization**
- *Lecture Topics:*
  - matplotlib fundamentals
  - seaborn for statistical visualization
  - Medical data visualization best practices
  - Interactive plots with plotly
- *Lab:* Create comprehensive medical data visualizations
- *Reading:* Visualization resources
- **Deliverable:** Group Lab 1 due

### Week 3: PyTorch Deep Dive

**Class 5: PyTorch Fundamentals**
- *Lecture Topics:*
  - Tensors in depth
  - Autograd and computational graphs
  - Building neural network modules
  - Training loops
  - GPU optimization
- *Lab:* Build first neural network from scratch
- *Reading:* Textbook Chapter 3

**Class 6: PyTorch Datasets & DataLoaders**
- *Lecture Topics:*
  - Dataset and DataLoader classes
  - Data augmentation for medical images
  - Batch processing
  - Custom dataset creation
- *Lab:* Create medical imaging dataset pipeline
- *Reading:* PyTorch documentation
- **Deliverable:** Group Lab 2 due

### Week 4: Linear Models

**Class 7: Linear Regression**
- *Lecture Topics:*
  - 1D and multi-dimensional linear regression
  - Least squares cost function
  - Closed-form solutions
  - Gradient descent
  - Input normalization
  - Regularization (L1, L2)
- *Lab:* Predict patient outcomes with linear regression
- *Reading:* Textbook Chapter 4

**Class 8: Linear Classification**
- *Lecture Topics:*
  - Binary classification
  - Logistic function and sigmoid
  - Cross-entropy loss
  - Multi-class classification (softmax)
  - Decision boundaries
- *Lab:* Disease classification with logistic regression
- *Reading:* Textbook Chapter 5
- **Deliverable:** Group Lab 3 due

---

## Phase 2: Healthcare Data (Weeks 5-6)

### Week 5: Healthcare Data Standards

**Class 9: HL7 FHIR Introduction**
- *Lecture Topics:*
  - Healthcare interoperability challenges
  - HL7 FHIR overview
  - FHIR resources (Patient, Observation, Condition)
  - RESTful API basics
  - Python FHIR libraries
- *Lab:* Parse and query FHIR resources
- *Reading:* FHIR specification

**Class 10: Electronic Health Records (EHR)**
- *Lecture Topics:*
  - EHR structure and challenges
  - Temporal data in EHRs
  - Missing data strategies
  - Feature engineering from EHRs
- *Lab:* Build patient cohort from MIMIC-III data
- *Reading:* MIMIC-III documentation
- **Deliverable:** Group Lab 4 due

### Week 6: Medical Imaging & Neural Networks

**Class 11: DICOM & Medical Imaging**
- *Lecture Topics:*
  - DICOM standard overview
  - Image modalities (X-ray, CT, MRI, ultrasound)
  - DICOM tags and metadata
  - Image preprocessing (windowing, normalization)
  - pydicom library
- *Lab:* Load and process DICOM images
- *Reading:* DICOM standard

**Class 12: Introduction to Neural Networks**
- *Lecture Topics:*
  - From feature engineering to feature learning
  - Perceptrons and multi-layer networks
  - Activation functions (ReLU, sigmoid, tanh)
  - Backpropagation intuition
  - Network architecture design
- *Lab:* Build fully connected network for medical imaging
- *Reading:* Textbook Chapter 6
- **Deliverable:** Group Lab 5 due

---

## Phase 3: Deep Learning (Weeks 7-9)

### Week 7: Convolutional Neural Networks

**Class 13: CNN Fundamentals**
- *Lecture Topics:*
  - Convolution operation
  - Filters and feature maps
  - Pooling layers
  - CNN architectures (LeNet, AlexNet, VGG)
  - Transfer learning
- *Lab:* Chest X-ray pneumonia detection
- *Reading:* Textbook Chapter 7

**Class 14: Advanced CNNs**
- *Lecture Topics:*
  - ResNet and skip connections
  - Inception modules
  - Medical image segmentation (U-Net)
  - Object detection for medical imaging
- *Lab:* Implement U-Net for organ segmentation
- *Reading:* Key CNN papers
- **Deliverable:** Group Lab 6 due

### Week 8: Recurrent Neural Networks & Midterm

**Class 15: RNN Fundamentals**
- *Lecture Topics:*
  - Sequence modeling challenges
  - Vanilla RNNs
  - LSTMs and GRUs
  - Bidirectional RNNs
  - Applications to time-series medical data
- *Lab:* ECG arrhythmia classification with LSTMs
- *Reading:* Textbook Chapter 7 (RNN section)

**Class 16: Attention & Transformers**
- *Lecture Topics:*
  - Attention mechanism
  - Transformer architecture
  - BERT for medical text
  - Clinical note processing
- *Lab:* Medical text classification with transformers
- *Reading:* "Attention is All You Need"
- **Deliverable:** Midterm Project due

### Week 9: Model Evaluation & Clinical Validation

**Class 17: Performance Metrics**
- *Lecture Topics:*
  - Classification metrics (accuracy, precision, recall, F1, AUC-ROC)
  - Regression metrics (MSE, MAE, R²)
  - Confusion matrices
  - Class imbalance handling
  - Cross-validation strategies
- *Lab:* Comprehensive model evaluation
- *Reading:* Textbook Chapter 8

**Class 18: Clinical Validation & Deployment**
- *Lecture Topics:*
  - Clinical vs. technical validation
  - Prospective vs. retrospective studies
  - FDA approval process for medical AI
  - Model monitoring in production
  - Failure modes in medical AI
- *Lab:* Model interpretability with SHAP/LIME
- *Reading:* FDA AI/ML guidance documents
- **Deliverable:** Group Lab 7 due

---

## Phase 4: Final Project (Weeks 10-14)

### Week 10: Ethics & Project Launch

**Class 19: Ethics, Bias, and Fairness**
- *Lecture Topics:*
  - Algorithmic bias in healthcare
  - Fairness metrics and trade-offs
  - Health equity considerations
  - HIPAA and patient privacy
  - Informed consent for AI
- *Lab:* Bias detection and mitigation
- *Reading:* Ethics papers and case studies

**Class 20: Final Project Kickoff**
- *Lecture Topics:*
  - Project scope and expectations
  - Dataset selection
  - Proposal components
  - Timeline and milestones
  - Team roles and responsibilities
- *Lab:* Project proposal development
- *Reading:* Example projects
- **Deliverable:** Project proposal due + Group Lab 8 due

### Week 11: Project Development I

**Class 21: Data Pipeline Workshop**
- *Activity:* Group work session with instructor feedback
- *Topics:* Data loading, preprocessing, augmentation
- *Milestone:* Data pipeline complete

**Class 22: Model Development Workshop**
- *Activity:* Group work session with instructor feedback
- *Topics:* Model architecture, baseline results
- *Milestone:* Initial model training complete

### Week 12: Project Development II

**Class 23: Evaluation Workshop**
- *Activity:* Group work session with instructor feedback
- *Topics:* Performance metrics, error analysis
- *Milestone:* Model evaluation complete

**Class 24: Interpretation Workshop**
- *Activity:* Group work session with instructor feedback
- *Topics:* Model interpretability, clinical insights
- *Milestone:* Interpretation complete

### Week 13: Project Development III

**Class 25: Deployment Preparation**
- *Activity:* Group work session
- *Topics:* Documentation, code quality, reproducibility
- *Milestone:* Code and documentation finalized

**Class 26: Presentation Practice**
- *Activity:* Practice presentations with peer feedback
- *Topics:* Storytelling, visualization, Q&A preparation
- *Milestone:* Presentation slides complete

### Week 14: Final Presentations & Wrap-up

**Class 27: Final Project Presentations (Part 1)**
- *Format:* 15 min presentation + 5 min Q&A per group
- *Audience:* Class + invited guests
- *Assessment:* Graded by instructors and peers

**Class 28: Final Project Presentations (Part 2) & Course Wrap-up**
- *Format:* Remaining presentations
- *Activity:* Course retrospective and feedback
- *Celebration:* Recognize outstanding projects
- **Deliverable:** Final project report and code due

---

## Assessment Summary

| Week | Deliverable | Type | Weight |
|------|-------------|------|--------|
| 2 | Group Lab 1 | Lab | 3.75% |
| 3 | Group Lab 2 | Lab | 3.75% |
| 4 | Group Lab 3 | Lab | 3.75% |
| 5 | Group Lab 4 | Lab | 3.75% |
| 6 | Group Lab 5 | Lab | 3.75% |
| 7 | Group Lab 6 | Lab | 3.75% |
| 8 | Midterm Project | Project | 15% |
| 9 | Group Lab 7 | Lab | 3.75% |
| 10 | Group Lab 8 + Proposal | Lab + Proposal | 3.75% |
| 14 | Final Project | Project | 40% |
| Ongoing | Individual Participation | Participation | 15% |

**Total: 100%**

---

## Learning Outcomes by Phase

### Phase 1: Foundations
✓ Understand ML pipeline and taxonomy
✓ Encode medical data as tensors
✓ Write Python code for data analysis
✓ Build and train linear models
✓ Evaluate model performance

### Phase 2: Healthcare Data
✓ Work with FHIR and DICOM standards
✓ Process EHR data
✓ Handle medical imaging data
✓ Build neural networks from scratch

### Phase 3: Deep Learning
✓ Implement CNNs for medical imaging
✓ Apply RNNs to time-series medical data
✓ Use transformers for clinical text
✓ Validate models clinically
✓ Understand ethical considerations

### Phase 4: Capstone Project
✓ Execute complete ML project end-to-end
✓ Collaborate effectively in teams
✓ Present technical work to diverse audiences
✓ Produce publication-quality results
