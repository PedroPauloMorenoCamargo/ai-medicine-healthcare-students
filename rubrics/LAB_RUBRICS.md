# Lab Grading Rubrics
## AI in Medicine and Healthcare
### Insper Instituto de Ensino e Pesquisa

---

## 📊 Lab Assessment Overview

**Total Lab Weight: 40%** (8 labs × 5% each)

| Week | Lab | Weight | Focus |
|------|-----|--------|-------|
| 2 | Lab 1: Python & Data Analysis | 5% | pandas, visualization, EDA |
| 3 | Lab 2: PyTorch Basics | 5% | Tensors, autograd, first neural net |
| 4 | Lab 3: Linear Models | 5% | Regression, classification |
| 5 | Lab 4: FHIR & EHR Data | 5% | Healthcare standards |
| 6 | Lab 5: Medical Imaging | 5% | DICOM, image processing |
| 7 | Lab 6: CNNs | 5% | Convolutional networks |
| 9 | Lab 7: Model Evaluation | 5% | Metrics, validation |
| 11 | Lab 8: Advanced Techniques | 5% | Optimization, ensembles |

---

## 🎯 General Lab Rubric (Applied to Each Lab)

Each lab is graded out of 5% using the following criteria:

### 1. Code Functionality (2%)

**Excellent (1.8-2.0%):**
- All cells run without errors
- Produces correct outputs
- Handles edge cases appropriately
- Efficient implementation
- No hard-coded values where variables should be used

**Good (1.4-1.7%):**
- Code runs successfully
- Correct outputs for main tasks
- Minor inefficiencies acceptable

**Satisfactory (1.0-1.3%):**
- Code mostly functional
- Some outputs correct
- May have minor errors in edge cases

**Needs Improvement (<1.0%):**
- Code has errors
- Incorrect outputs
- Incomplete implementation

---

### 2. Code Quality (0.5%)

**Excellent (0.45-0.5%):**
- Clear variable names
- Appropriate comments
- Consistent formatting
- Functions/classes used appropriately
- Follows Python conventions (PEP 8)

**Good (0.35-0.4%):**
- Generally clean code
- Some comments
- Readable

**Satisfactory (0.25-0.3%):**
- Code works but messy
- Limited comments

**Needs Improvement (<0.25%):**
- Very messy code
- No comments
- Unclear structure

---

### 3. Analysis & Interpretation (1.5%)

**Excellent (1.3-1.5%):**
- Thoughtful analysis of results
- Visualizations well-designed and labeled
- Insights clearly articulated
- Medical context considered
- Answers all questions thoroughly
- Goes beyond minimum requirements

**Good (1.0-1.2%):**
- Analysis present
- Visualizations included
- Questions answered
- Basic interpretation

**Satisfactory (0.7-0.9%):**
- Minimal analysis
- Basic visualizations
- Questions addressed briefly

**Needs Improvement (<0.7%):**
- Little to no analysis
- Missing visualizations
- Questions not answered

---

### 4. Understanding (1%)

**Excellent (0.9-1.0%):**
- Demonstrates deep understanding of concepts
- Can explain code choices
- Identifies and fixes bugs independently
- Explores beyond provided code
- Makes meaningful modifications

**Good (0.7-0.8%):**
- Shows understanding of main concepts
- Can explain code
- Completes all tasks

**Satisfactory (0.5-0.6%):**
- Basic understanding
- Follows instructions
- Limited exploration

**Needs Improvement (<0.5%):**
- Minimal understanding
- Copy-paste without comprehension
- Cannot explain code

---

## 📝 Lab-Specific Details

### Lab 1: Python & Data Analysis (Week 2, 5%)

**Key Skills Assessed:**
- pandas DataFrame operations
- Data cleaning and handling missing values
- Statistical summaries
- Data visualization (matplotlib, seaborn)
- Exploratory data analysis

**Specific Requirements:**
- Load and explore medical dataset
- Handle missing values appropriately
- Compute descriptive statistics
- Create at least 3 meaningful visualizations
- Identify patterns or insights in data

---

### Lab 2: PyTorch Basics (Week 3, 5%)

**Key Skills Assessed:**
- Tensor creation and manipulation
- Autograd and gradient computation
- Building simple neural networks
- Training loop implementation
- Loss functions and optimizers

**Specific Requirements:**
- Create and manipulate tensors
- Implement forward and backward pass
- Build a simple neural network
- Train on provided dataset
- Plot training curves (loss vs. epochs)

---

### Lab 3: Linear Models (Week 4, 5%)

**Key Skills Assessed:**
- Linear regression implementation
- Logistic regression for classification
- Cost function understanding
- Gradient descent
- Model evaluation

**Specific Requirements:**
- Implement linear regression from scratch
- Implement logistic regression
- Train on medical dataset
- Evaluate with appropriate metrics
- Visualize decision boundaries

---

### Lab 4: FHIR & EHR Data (Week 5, 5%)

**Key Skills Assessed:**
- FHIR resource parsing
- Working with JSON medical data
- EHR data extraction
- Temporal data handling
- Feature engineering from clinical data

**Specific Requirements:**
- Parse FHIR resources
- Extract relevant medical information
- Build patient cohort
- Create features for ML
- Handle temporal aspects

---

### Lab 5: Medical Imaging (Week 6, 5%)

**Key Skills Assessed:**
- DICOM file handling
- Image preprocessing
- Normalization and augmentation
- Medical image visualization
- Dataset creation

**Specific Requirements:**
- Load DICOM images
- Apply preprocessing (windowing, normalization)
- Create data augmentation pipeline
- Build PyTorch Dataset
- Visualize medical images correctly

---

### Lab 6: CNNs (Week 7, 5%)

**Key Skills Assessed:**
- CNN architecture design
- Convolutional layers
- Pooling and batch normalization
- Transfer learning
- Medical image classification

**Specific Requirements:**
- Implement CNN from scratch
- Use transfer learning (ResNet, VGG)
- Train on medical images
- Evaluate performance
- Visualize learned features

---

### Lab 7: Model Evaluation (Week 9, 5%)

**Key Skills Assessed:**
- Classification metrics
- Confusion matrix analysis
- ROC curves and AUC
- Cross-validation
- Statistical testing

**Specific Requirements:**
- Compute multiple metrics (accuracy, precision, recall, F1)
- Create and interpret confusion matrix
- Plot and analyze ROC curve
- Perform k-fold cross-validation
- Compare models statistically

---

### Lab 8: Advanced Techniques (Week 11, 5%)

**Key Skills Assessed:**
- Hyperparameter tuning
- Ensemble methods
- Model optimization
- Regularization techniques
- Advanced PyTorch features

**Specific Requirements:**
- Implement hyperparameter search
- Build ensemble model
- Apply regularization
- Optimize training
- Achieve performance targets

---

## 🔄 Submission Requirements

### Format
- Jupyter notebook (.ipynb)
- All cells executed with outputs visible
- Markdown cells with explanations
- Clear section headers
- Name: `Lastname_Firstname_Lab#.ipynb`

### Submission Method
- Upload to Blackboard by deadline
- Or: Push to GitHub and submit link

### Due Date
- End of the week (Sunday 11:59 PM)
- Late penalty: -10% per day up to 2 days
- After 48 hours: contact instructor

---

## ✅ Lab Completion Checklist

Before submitting each lab, verify:

- [ ] All code cells run without errors
- [ ] Outputs are visible for all cells
- [ ] Required visualizations included
- [ ] Questions answered in markdown cells
- [ ] Code is commented appropriately
- [ ] Variable names are clear
- [ ] Medical context considered in analysis
- [ ] File named correctly
- [ ] Submitted on time

---

## 🤝 Collaboration Policy

### Allowed:
- ✅ Discuss concepts with classmates
- ✅ Help debug errors together
- ✅ Share resources (tutorials, documentation)
- ✅ Study together

### Not Allowed:
- ❌ Copy code from classmates
- ❌ Submit identical notebooks
- ❌ Use solutions from previous years
- ❌ Have someone else do your work

**Suspected violations will be investigated and may result in zero credit.**

---

## 💡 Tips for Success

### Before Starting
1. Review lecture materials
2. Read the assignment carefully
3. Check if special libraries needed
4. Allocate 2-3 hours

### During the Lab
1. Start early (don't wait until deadline!)
2. Test code incrementally
3. Save frequently
4. Add comments as you code
5. Ask for help if stuck >30 minutes

### Before Submitting
1. Restart kernel and run all cells
2. Check all outputs visible
3. Review rubric
4. Proofread markdown cells
5. Submit with time to spare

---

## 📊 Grade Distribution Example

**Sample Lab Grading:**

| Component | Points Possible | Points Earned | Notes |
|-----------|----------------|---------------|-------|
| Code Functionality | 2.0% | 1.8% | All tasks complete, minor inefficiency |
| Code Quality | 0.5% | 0.4% | Good structure, could use more comments |
| Analysis & Interpretation | 1.5% | 1.4% | Strong analysis, excellent visualizations |
| Understanding | 1.0% | 0.9% | Demonstrated deep understanding |
| **Total** | **5.0%** | **4.5%** | **Excellent work!** |

---

## 🆘 Getting Help

### During Lab Time
- Raise hand for TA assistance
- Work with lab partner
- Ask instructor

### Outside Lab Time
- Office hours (schedule on Blackboard)
- Discussion board (post questions)
- Email TA (allow 24 hours)

### Resources
- Course materials on GitHub
- PyTorch documentation
- StackOverflow (cite if you use!)
- Course Slack/Discord

---

## 🎯 Learning Objectives

Labs are designed to help you:
- **Practice** concepts from lecture
- **Build** coding skills incrementally
- **Apply** ML to real medical data
- **Develop** good coding habits
- **Prepare** for project work

**Labs build on each other - stay on track!**

---

## 📈 Lab Performance Tracking

| Lab | Score | Running Average | Notes |
|-----|-------|----------------|-------|
| Lab 1 | /5% | - | Python & pandas |
| Lab 2 | /5% | - | PyTorch basics |
| Lab 3 | /5% | - | Linear models |
| Lab 4 | /5% | - | FHIR & EHR |
| Lab 5 | /5% | - | Medical imaging |
| Lab 6 | /5% | - | CNNs |
| Lab 7 | /5% | - | Evaluation |
| Lab 8 | /5% | - | Advanced techniques |
| **Total** | **/40%** | - | - |

**Track your progress - aim for consistent performance!**

---

**Work hard, learn deeply, and build a strong foundation for your project!**
