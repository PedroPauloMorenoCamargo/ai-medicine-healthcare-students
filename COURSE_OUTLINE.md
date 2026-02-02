# AI in Medicine and Healthcare - Revised Course Outline
## Single Project Focus (No Midterm)

**Institution:** Insper Instituto de Ensino e Pesquisa, São Paulo, Brazil  
**Target Audience:** Engineering and Computer Science students  
**Course Type:** Elective/Specialization

---

## 📋 Course Structure Changes

### **Old Structure:**
- 30% Labs (8 weekly)
- 15% Midterm Project
- 40% Final Project
- 15% Participation

### **New Structure:** ⭐
- **40% Labs** (8 weekly, 5% each)
- **45% Group Project** (single comprehensive project)
- **15% Participation**

**Total: 100%**

---

## 🎯 Project Timeline Overview

| Week | Project Milestone | Weight | Deliverable |
|------|------------------|--------|-------------|
| 1-3 | Exploration & Ideation | - | Informal brainstorming |
| 4 | **Proposal Submission** | 5% | 2-page project proposal |
| 5 | Proposal Feedback & Refinement | - | Revised proposal (if needed) |
| 6 | Dataset Acquisition & EDA | 5% | Dataset ready, initial analysis |
| 8 | **Progress Report 1** | 10% | Model baseline, preliminary results |
| 10 | **Progress Report 2** | 10% | Advanced modeling, interpretation |
| 12 | Code & Documentation Review | 5% | Complete codebase, reproducibility check |
| 14 | **Final Presentation** | 10% | 15-min presentation + Q&A |
| 14 | **Final Report & Code** | 15% | Complete deliverable package |

**Project Total: 60% (including 15% participation)**

---

## 📅 Detailed 14-Week Schedule

### **Phase 1: Foundations + Project Launch (Weeks 1-5)**

#### **Week 1: Introduction to ML & Mathematical Encoding**

**Class 1: Introduction to Machine Learning**
- ML Pipeline, Curse of Dimensionality, ML Taxonomy
- **Lab:** Python, NumPy, pandas with Pima diabetes dataset
- **Project:** None yet (focus on foundations)

**Class 2: Mathematical Encoding of Medical Data**
- 6 data types, PyTorch tensors, GPU acceleration
- **Lab:** Tensor operations, medical data encoding
- **Project:** Start thinking about medical AI interests

---

#### **Week 2: Python Fundamentals**

**Class 3: Python, NumPy & pandas**
- Data structures, array operations, DataFrames
- **Lab:** Medical dataset exploration, missing data handling
- **Project:** Browse potential datasets (Kaggle, PhysioNet, Grand Challenge)

**Class 4: Data Visualization**
- matplotlib, seaborn, medical visualization best practices
- **Lab:** Create comprehensive medical data visualizations
- **Deliverable:** Group Lab 1 due (5%)

---

#### **Week 3: PyTorch Deep Dive**

**Class 5: PyTorch Fundamentals**
- Tensors, autograd, computational graphs, training loops
- **Lab:** Build first neural network from scratch
- **Project:** Form groups (3-4 students), discuss interests

**Class 6: PyTorch Datasets & DataLoaders**
- Dataset/DataLoader classes, data augmentation, batch processing
- **Lab:** Create medical imaging dataset pipeline
- **Deliverable:** Group Lab 2 due (5%)
- **Project:** Groups finalized, brainstorming sessions

---

#### **Week 4: Linear Models + Project Proposal**

**Class 7: Linear Regression**
- Multi-dimensional regression, gradient descent, regularization
- **Lab:** Predict patient outcomes with linear regression
- **Project:** Draft proposal (topic, dataset, objectives)

**Class 8: Linear Classification**
- Logistic regression, softmax, multi-class classification
- **Lab:** Disease classification with logistic regression
- **Deliverable:** Group Lab 3 due (5%)
- **🎯 PROJECT PROPOSAL DUE (5%)**

**Proposal Requirements:**
- 2-3 pages (excluding references)
- Medical problem statement
- Dataset description (with availability confirmation)
- Proposed approach (ML/DL methods)
- Expected outcomes
- Timeline
- Team member roles

---

#### **Week 5: Healthcare Data Standards + Proposal Refinement**

**Class 9: HL7 FHIR Introduction**
- Healthcare interoperability, FHIR resources, RESTful APIs
- **Lab:** Parse and query FHIR resources
- **Project:** Instructor feedback on proposals

**Class 10: Electronic Health Records (EHR)**
- EHR structure, temporal data, feature engineering
- **Lab:** Build patient cohort from MIMIC-III data
- **Deliverable:** Group Lab 4 due (5%)
- **Project:** Revised proposals (if needed), dataset acquisition begins

---

### **Phase 2: Healthcare Data + Early Development (Weeks 6-7)**

#### **Week 6: Medical Imaging + Dataset Preparation**

**Class 11: DICOM & Medical Imaging**
- DICOM standard, image modalities, preprocessing
- **Lab:** Load and process DICOM images
- **🎯 PROJECT MILESTONE: Dataset + EDA (5%)**

**Requirements:**
- Dataset acquired and loaded
- Exploratory data analysis complete
- Data quality assessment
- Preprocessing pipeline defined
- 1-page report + code

**Class 12: Introduction to Neural Networks**
- Perceptrons, multi-layer networks, backpropagation
- **Lab:** Build fully connected network for medical imaging
- **Deliverable:** Group Lab 5 due (5%)

---

#### **Week 7: Convolutional Neural Networks**

**Class 13: CNN Fundamentals**
- Convolution, pooling, CNN architectures, transfer learning
- **Lab:** Chest X-ray pneumonia detection
- **Project:** Baseline model development

**Class 14: Advanced CNNs**
- ResNet, U-Net for segmentation, object detection
- **Lab:** Implement U-Net for organ segmentation
- **Deliverable:** Group Lab 6 due (5%)
- **Project:** Baseline results ready for Progress Report 1

---

### **Phase 3: Deep Learning + Iterative Development (Weeks 8-11)**

#### **Week 8: RNNs + Progress Report 1**

**Class 15: RNN Fundamentals**
- Sequence modeling, LSTMs, GRUs, bidirectional RNNs
- **Lab:** ECG arrhythmia classification with LSTMs
- **Project:** Continue model development

**Class 16: Attention & Transformers**
- Attention mechanism, Transformer architecture, BERT
- **Lab:** Medical text classification with transformers
- **🎯 PROGRESS REPORT 1 DUE (10%)**

**Progress Report 1 Requirements:**
- 3-4 pages
- Dataset description and statistics
- Baseline model architecture
- Initial results (accuracy, loss curves)
- Challenges encountered
- Next steps
- Updated timeline

---

#### **Week 9: Model Evaluation & Clinical Validation**

**Class 17: Performance Metrics**
- Classification/regression metrics, confusion matrices, cross-validation
- **Lab:** Comprehensive model evaluation
- **Project:** Refine models based on Progress Report 1 feedback

**Class 18: Clinical Validation & Deployment**
- Clinical vs. technical validation, FDA approval, model monitoring
- **Lab:** Model interpretability with SHAP/LIME
- **Deliverable:** Group Lab 7 due (5%)
- **Project:** Advanced modeling phase

---

#### **Week 10: Ethics + Progress Report 2**

**Class 19: Ethics, Bias, and Fairness**
- Algorithmic bias, fairness metrics, health equity, HIPAA
- **Lab:** Bias detection and mitigation
- **Project:** Incorporate ethical considerations

**Class 20: Advanced Techniques Workshop**
- Hyperparameter tuning, ensemble methods, optimization
- **Lab:** Improve model performance
- **🎯 PROGRESS REPORT 2 DUE (10%)**

**Progress Report 2 Requirements:**
- 4-5 pages
- Advanced model architecture(s)
- Comparison of approaches
- Performance analysis (including fairness metrics)
- Clinical interpretation of results
- Model limitations
- Plans for final deliverable

---

#### **Week 11: Project Development & Mentoring**

**Class 21: Code Quality & Reproducibility**
- Clean code practices, documentation, version control, reproducible research
- **Workshop:** Code review with instructor/TAs
- **Project:** Code cleanup and documentation

**Class 22: Visualization & Communication**
- Scientific visualization, creating figures for papers/presentations
- **Workshop:** Practice presentations with peer feedback
- **Deliverable:** Group Lab 8 due (5%)
- **Project:** Finalize results and visualizations

---

### **Phase 4: Finalization & Presentation (Weeks 12-14)**

#### **Week 12: Documentation & Peer Review**

**Class 23: Writing for Technical Audiences**
- Structure of ML papers, clear methodology, results reporting
- **Workshop:** Draft final report, peer review session
- **Project:** Write final report

**Class 24: Deployment Considerations**
- Docker, APIs, model serving, monitoring in production
- **Workshop:** Create deployment documentation
- **🎯 CODE & DOCUMENTATION REVIEW (5%)**

**Requirements:**
- Complete, runnable codebase on GitHub
- README with setup instructions
- Requirements.txt or environment.yml
- Clear code structure and comments
- Reproducible results
- CI/CD optional but encouraged

---

#### **Week 13: Presentation Preparation**

**Class 25: Effective Scientific Presentations**
- Storytelling with data, slide design, handling Q&A
- **Workshop:** Mock presentations with feedback
- **Project:** Finalize presentation slides

**Class 26: Presentation Practice Session**
- Each group presents to class (informal, practice run)
- Peer and instructor feedback
- Q&A practice
- **Project:** Incorporate feedback into final presentation

---

#### **Week 14: Final Presentations & Course Wrap-up**

**Class 27: Final Project Presentations (Part 1)**
- **Format:** 15 min presentation + 5 min Q&A per group
- **Audience:** Class + invited guests (clinicians, researchers)
- **Presentation slides due before class**
- **🎯 FINAL PRESENTATION (10%)**

**Class 28: Final Presentations (Part 2) & Course Celebration**
- Remaining presentations
- Best project awards (peer + instructor voting)
- Course retrospective and feedback
- Networking and celebration
- **🎯 FINAL REPORT & CODE DUE (15%)**

**Final Deliverable Package:**
- Final report (8-10 pages, conference paper format)
- Complete codebase (GitHub repository)
- Presentation slides
- Demo video (3-5 min, optional but encouraged)
- Data availability statement
- Individual contribution statements

---

## 📊 Complete Grading Breakdown

### Labs: 40% (8 labs × 5% each)
| Week | Lab | Weight |
|------|-----|--------|
| 2 | Lab 1: Python & Data Analysis | 5% |
| 3 | Lab 2: PyTorch Basics | 5% |
| 4 | Lab 3: Linear Models | 5% |
| 5 | Lab 4: FHIR & EHR Data | 5% |
| 6 | Lab 5: Medical Imaging | 5% |
| 7 | Lab 6: CNNs | 5% |
| 9 | Lab 7: Model Evaluation | 5% |
| 11 | Lab 8: Advanced Techniques | 5% |

### Group Project: 45%
| Week | Milestone | Weight |
|------|-----------|--------|
| 4 | Project Proposal | 5% |
| 6 | Dataset + EDA | 5% |
| 8 | Progress Report 1 | 10% |
| 10 | Progress Report 2 | 10% |
| 12 | Code & Documentation | 5% |
| 14 | Final Presentation | 10% |
| 14 | Final Report & Code | 15% |

### Participation: 15%
- Attendance (5%)
- In-class engagement (5%)
- Peer feedback & collaboration (5%)

**Total: 100%**

---

## 🎯 Project Requirements Summary

### Minimum Requirements
- **Medical relevance:** Clear healthcare application
- **Dataset size:** Sufficient for ML (minimum ~500 samples)
- **Model complexity:** Beyond baseline (not just logistic regression)
- **Evaluation:** Proper train/test split, multiple metrics
- **Interpretation:** Clinical significance of results
- **Ethics:** Consider bias, fairness, privacy
- **Reproducibility:** Complete code and documentation

### Encouraged Elements
- Novel dataset or approach
- Multiple model comparisons
- Clinical validation considerations
- Deployment readiness
- Collaboration with medical professionals
- Publication-quality deliverables

### Topic Examples
- Disease diagnosis from medical imaging
- Clinical outcome prediction from EHR
- Drug response prediction from genomics
- Medical text analysis (radiology reports, clinical notes)
- Time-series analysis (ECG, EEG, vital signs)
- Multi-modal fusion (imaging + clinical data)

---

## 📝 Individual Grade Adjustments

- Base grade from group deliverables
- Individual adjustments ±15% based on:
  - Peer evaluations (after each milestone)
  - Individual contribution statements
  - Code commit history (GitHub insights)
  - Meeting participation (instructor observations)

**Consistently low contribution = significant grade reduction**

---

## 🎓 Learning Outcomes

By the end of the course, students will:

**Technical Skills:**
- ✅ Design and implement complete ML pipelines
- ✅ Work with diverse medical data types
- ✅ Build and evaluate deep learning models
- ✅ Process medical images, EHR data, and genomics
- ✅ Deploy models with proper documentation

**Domain Knowledge:**
- ✅ Understand medical AI landscape
- ✅ Navigate healthcare data standards
- ✅ Consider clinical validation requirements
- ✅ Address ethical issues (bias, fairness, privacy)
- ✅ Communicate with medical professionals

**Professional Skills:**
- ✅ Collaborate effectively in teams
- ✅ Manage long-term technical projects
- ✅ Present technical work to diverse audiences
- ✅ Write clear documentation and reports
- ✅ Incorporate iterative feedback

**Project Management:**
- ✅ Scope and plan ambitious projects
- ✅ Meet progressive deadlines
- ✅ Pivot when needed based on challenges
- ✅ Deliver publication-quality work

---

## 📚 Student Support Structure

### Regular Check-ins
- **Weeks 4-14:** Weekly project office hours
- **After each milestone:** Detailed written feedback

### Resources Provided
- Project proposal templates
- Progress report rubrics
- Final report template (conference paper format)
- Presentation rubric
- Dataset suggestions and access guidance

### Flexibility
- Can pivot project direction at Progress Report 1 (Week 8)
- Extensions available for documented challenges
- Group reconfiguration possible (with approval)

---

**Next: See detailed rubrics for each project component!**
