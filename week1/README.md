# Week 1: Introduction to ML & Mathematical Encoding

## 🎯 Learning Objectives

By the end of Week 1, you will be able to:
- ✅ Explain the 4-step ML pipeline
- ✅ Understand why ML is necessary for medical applications  
- ✅ Encode 6 types of medical data as tensors
- ✅ Create and manipulate PyTorch tensors
- ✅ Load and explore medical datasets using pandas
- ✅ Perform basic data visualization and analysis

---

## 📅 Class Schedule

### 🔵 Class 1: Introduction to Machine Learning (Tuesday)

**⏰ Time:** 30-40 min lecture + 80-90 min lab

#### Lecture Topics
- Why machine learning in medicine?
- From ELIZA to modern AI: rule-based → data-driven
- The ML pipeline: Data → Features → Training → Testing
- Deep dive into each pipeline step
- The curse of dimensionality
- ML taxonomy (supervised, unsupervised, reinforcement)

#### 📊 Lecture Slides
[**Download Presentation**](presentations/Week1_Class1_Introduction_ML.pptx)

#### 💻 Hands-On Lab

**Open directly in Colab (One Click!):**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/ai-ml-medicine-course-students/blob/main/week1/notebooks/Week1_Class1_Introduction_and_Colab_Setup.ipynb)

**What you'll do:**
- Set up Google Colab environment
- Review Python basics
- Learn NumPy array operations
- Use pandas DataFrames for medical data
- Load Pima Indians Diabetes dataset (768 patients, 8 features)
- Calculate basic statistics
- Create visualizations

**Dataset:** Pima Indians Diabetes (768 patients)
- 8 clinical features (glucose, BMI, age, etc.)
- Binary outcome (diabetes yes/no)
- Perfect for learning ML fundamentals

#### 📖 Reading
- Textbook Chapter 1: Introduction
- [Getting Started Guide](../resources/Getting_Started.md) - If you haven't already

---

### 🔵 Class 2: Mathematical Encoding of Medical Data (Thursday)

**⏰ Time:** 30-35 min lecture + 85-90 min lab

#### Lecture Topics
- Why mathematical encoding matters
- Six types of medical data:
  1. **Numerical** - Vitals, lab results
  2. **Categorical** - Blood types, diagnoses (one-hot encoding)
  3. **Imaging** - X-rays, MRI, CT scans
  4. **Time-series** - ECG, EEG signals
  5. **Text** - Clinical notes, reports
  6. **Genomics** - DNA, RNA sequences
- PyTorch tensors: 0-D (scalar), 1-D (vector), 2-D (matrix), 3-D+
- Tensor operations and shapes
- GPU acceleration basics

#### 📊 Lecture Slides
[**Download Presentation**](presentations/Week1_Class2_Mathematical_Encoding.pptx)

#### 💻 Hands-On Lab

**Open directly in Colab (One Click!):**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/ai-ml-medicine-course-students/blob/main/week1/notebooks/Week1_Class2_PyTorch_Tensors.ipynb)

**What you'll do:**
- Create tensors of various dimensions (0-D, 1-D, 2-D, 3-D)
- Understand tensor shapes and reshaping
- Convert between NumPy and PyTorch
- Encode patient vital signs as tensors
- One-hot encode categorical medical variables (blood type, gender)
- Process simulated ECG time-series data
- Batch multiple patient records into matrices
- Try GPU operations with `.to('cuda')`

#### 📖 Reading
- Textbook Chapter 2: Mathematical Encoding of Medical Data

---

## 📚 Key Concepts

### The ML Pipeline

Every ML project follows these 4 steps:

```
1. DATA COLLECTION → 2. FEATURE DESIGN → 3. MODEL TRAINING → 4. MODEL TESTING
```

**1. Data Collection**
- Gather labeled examples (e.g., skin lesion images labeled benign/malignant)
- Split into training (70-90%) and testing (10-30%)
- NO OVERLAP between train and test!

**2. Feature Design**
- Transform raw data into meaningful measurements
- Example: Skin lesion → symmetry score, border regularity
- Goal: Features that separate classes clearly

**3. Model Training**
- Find optimal line/boundary separating classes
- Minimize cost function (number of errors)
- Mathematical optimization

**4. Model Testing**
- Evaluate on completely new, unseen data
- Calculate accuracy: Correct predictions / Total samples
- Tests generalization ability

### The Curse of Dimensionality

**Problem:** Data needed grows exponentially with dimensions!

- 1D space: 3 sensors needed
- 2D space: 9 sensors (3²)
- 3D space: 27 sensors (3³)
- ND space: 3^N sensors

**Why it matters:**
- Raw pixel values: 512×512×3 = ~800,000 dimensions!
- Would need astronomical amounts of data
- Solution: Feature engineering or deep learning

### Medical Data Encoding

```python
# Numerical data - already numeric
vitals = torch.tensor([120.0, 80.0, 98.6, 72.0])  
# [systolic BP, diastolic BP, temp, heart rate]

# Categorical data - one-hot encoding
blood_type_A = torch.tensor([1, 0, 0, 0])   # A, B, AB, O
blood_type_O = torch.tensor([0, 0, 0, 1])

# Imaging data - 3D tensor
xray = torch.randn(1, 512, 512)      # [Channels, Height, Width]
rgb_image = torch.randn(3, 512, 512) # RGB channels

# Time-series - 2D tensor
ecg_24hr = torch.randn(86400, 12)    # [Time points, Leads]
```

---

## 🛠️ Technical Setup

### Before Class 1
- [ ] Create Google account (if needed)
- [ ] Test access to [Google Colab](https://colab.research.google.com)
- [ ] Review Python basics if rusty
- [ ] Read Getting Started guide

### Before Class 2
- [ ] Complete Class 1 lab
- [ ] Review linear algebra basics (vectors, matrices)
- [ ] Read Textbook Chapter 1

---

## 💡 Tips for Success

### During Labs

**Save Your Work!**
```
File → Save a copy in Drive
```
Do this IMMEDIATELY when you open a Colab notebook!

**Run Cells in Order**
- Execute cells from top to bottom
- Don't skip cells (they build on each other)
- Rerun if you get errors

**Experiment!**
- Change values and see what happens
- Break things (you can always restart)
- Add your own cells to try ideas

**Ask Questions!**
- Instructors and TAs are there to help
- No question is too basic
- Stuck for >10 minutes? Ask!

### Common Colab Issues

**Session Disconnected?**
```
Runtime → Reconnect
Runtime → Run all (to restore state)
```

**Module not found?**
```python
!pip install package-name
# Then: Runtime → Restart runtime
```

**CUDA out of memory?**
```python
import torch
torch.cuda.empty_cache()
# Or: Runtime → Factory reset runtime
```

---

## 📝 Homework (Recommended, Not Graded)

After Week 1, reinforce your learning:

1. **Practice Python**
   - Work through [Python Tutorial](https://docs.python.org/3/tutorial/) Chapters 3-5
   - Review NumPy and pandas basics

2. **Explore the Dataset**
   - Load Pima diabetes dataset
   - Create your own visualizations
   - Find interesting patterns

3. **Tensor Exercises**
   - Create tensors for your own medical data examples
   - Practice reshaping and operations
   - Try different encoding strategies

4. **Read Ahead**
   - Textbook Chapter 3 (Elementary Functions) - preview for Week 2

---

## 🎯 Self-Assessment

After Week 1, you should be able to:

**Class 1 Skills:**
- [ ] Explain the difference between rule-based AI and machine learning
- [ ] Describe all 4 steps of the ML pipeline
- [ ] Load a CSV dataset with pandas
- [ ] Calculate mean, median, std of medical data
- [ ] Create histograms and scatter plots
- [ ] Explain the curse of dimensionality

**Class 2 Skills:**
- [ ] Create PyTorch tensors of various dimensions
- [ ] Check and manipulate tensor shapes
- [ ] Convert between NumPy arrays and PyTorch tensors
- [ ] One-hot encode categorical variables
- [ ] Encode numerical medical data
- [ ] Understand tensor operations (add, multiply, reshape)

**Not there yet?** That's okay!
- Review the notebooks
- Try the exercises again
- Attend office hours
- Ask on discussion board

---

## 📊 What's Next?

### Week 2 Preview: Python Fundamentals

**Class 3:** Python, NumPy & pandas deep dive
- Advanced DataFrame operations
- Data cleaning and preprocessing
- Exploratory data analysis

**Class 4:** Data Visualization
- matplotlib and seaborn
- Medical data visualization best practices
- Interactive plots

**First graded assignment:** Group Lab 1 due end of Week 2!

---

## 🔗 Quick Links

- **Main Course Page:** [README.md](../README.md)
- **Full Schedule:** [COURSE_OUTLINE.md](../COURSE_OUTLINE.md)
- **Getting Started:** [Getting_Started.md](../resources/Getting_Started.md)
- **FAQ:** [FAQ.md](../resources/FAQ.md)
- **Grading Rubrics:** [rubrics/](../rubrics/)

---

## ❓ Questions?

- **Technical issues:** Check [FAQ](../resources/FAQ.md) first
- **Colab help:** [Official Colab FAQ](https://research.google.com/colaboratory/faq.html)
- **Course questions:** Post on Blackboard discussion board
- **Private concerns:** Email instructor
- **Need help?** Attend office hours!

---

**You've got this! Welcome to AI in Medicine! 🏥🤖**
