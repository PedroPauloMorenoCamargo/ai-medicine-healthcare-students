# Week 1 Lab Grading Rubrics
## AI/ML in Medicine and Healthcare

---

## Overview

These rubrics provide detailed criteria for evaluating student work on Week 1 lab assignments. Each lab is graded holistically but with specific attention to the categories below.

**Total Points per Lab:** 100 points  
**Weight in Course:** Each Week 1 lab = Individual assessment (not group work)  
**Due:** End of week

---

## Class 1: Introduction to ML and Colab Setup

### Rubric Breakdown

| Category | Excellent (90-100%) | Proficient (75-89%) | Developing (60-74%) | Needs Improvement (<60%) | Points |
|----------|---------------------|---------------------|---------------------|--------------------------|--------|
| **Completion** (40 pts) | All code cells executed successfully; all exercises completed; reflection questions answered thoughtfully | Most cells executed; minor gaps in exercises; basic reflections provided | Several cells not executed or contain errors; some exercises incomplete; minimal reflections | Many incomplete sections; numerous errors; missing reflections | /40 |
| **Code Quality** (25 pts) | Clean, well-commented code; follows Python best practices; efficient use of libraries | Code mostly clean with some comments; generally follows conventions | Code works but lacks comments; some inefficient approaches | Messy code; few/no comments; significant inefficiencies | /25 |
| **Analysis & Insights** (20 pts) | Demonstrates deep understanding; insightful observations; correct interpretations of results; goes beyond requirements | Good understanding shown; reasonable observations; mostly correct interpretations | Basic understanding; superficial observations; some misinterpretations | Limited understanding; incorrect or missing observations | /20 |
| **Visualizations** (10 pts) | All plots clear, well-labeled, and informative; appropriate plot types chosen | Most plots good; minor labeling issues; generally appropriate | Some plots unclear or poorly labeled; questionable choices | Many plots missing or unusable | /10 |
| **Documentation** (5 pts) | Excellent markdown notes; clear explanations of approach; well-organized | Good documentation; clear structure | Minimal documentation; organization unclear | Little to no documentation | /5 |

**Total: /100 points**

---

### Detailed Scoring Criteria

#### Part 1-2: Setup & Libraries (10 points)
- ✓ Successfully mounted Google Drive (3 pts)
- ✓ Created course folder (2 pts)
- ✓ Imported all required libraries (3 pts)
- ✓ Set random seed for reproducibility (2 pts)

#### Part 3: Data Loading (10 points)
- ✓ Successfully loaded dataset (4 pts)
- ✓ Displayed basic information (df.head(), df.info()) (3 pts)
- ✓ Generated statistical summary (3 pts)

#### Part 4: Observation Questions (15 points)
**Question 1:** Average glucose level
- Full credit (5 pts): Correctly identifies ~120.9 mg/dL
- Partial (3 pts): Close value but not precise
- No credit (0 pts): Incorrect or missing

**Question 2:** Age range
- Full credit (5 pts): Correctly identifies 21-81 years
- Partial (3 pts): Identifies range but imprecise
- No credit (0 pts): Incorrect or missing

**Question 3:** Unusual values
- Full credit (5 pts): Identifies zeros in BP, Insulin, BMI, SkinThickness AND explains these are likely missing data
- Partial (3 pts): Identifies some zeros but incomplete explanation
- Minimal (1 pt): Notes something unusual but unclear
- No credit (0 pts): Missing or incorrect

#### Part 5: NumPy Operations (10 points)
- ✓ Correctly calculated mean/std for glucose and BMI (4 pts)
- ✓ BMI categorization implemented correctly (4 pts)
- ✓ Interpreted percentages correctly (2 pts)

#### Part 6: Visualizations (15 points)
- ✓ Outcome distribution bar chart (5 pts)
- ✓ Glucose histogram by diabetes status (5 pts)
- ✓ Age vs BMI scatter plot (5 pts)
- Quality: Clear labels, legends, appropriate colors

#### Part 7: Correlation Analysis (15 points)
**Question 1:** Strongest correlation
- Full credit (5 pts): Correctly identifies Glucose (r ≈ 0.47)
- Partial (3 pts): Identifies correct feature but wrong value
- No credit (0 pts): Incorrect

**Question 2:** Highly correlated features
- Full credit (5 pts): Identifies at least 2 pairs (Age-Pregnancies, SkinThickness-BMI, etc.) with approximate correlation values
- Partial (3 pts): Identifies 1 pair or correct pairs without values
- No credit (0 pts): Incorrect or missing

**Question 3:** Feature removal considerations
- Excellent (5 pts): Thoughtful discussion of SkinThickness/Insulin due to missing data; mentions testing approach
- Good (3 pts): Identifies problematic features but limited reasoning
- Poor (1 pt): Vague answer
- No credit (0 pts): Missing

#### Part 8: Simple ML Prediction (10 points)
- ✓ Calculated average glucose by group (3 pts)
- ✓ Implemented threshold-based prediction (4 pts)
- ✓ Calculated accuracy correctly (~74-75%) (3 pts)

#### Part 9: Exercise - Feature Engineering (10 points)
- ✓ Created risk score feature (4 pts)
- ✓ Tested predictive value (3 pts)
- ✓ Compared to glucose-only approach (3 pts)

#### Part 10: Reflection Questions (5 points)
- Each reflection question worth ~1.67 pts
- Full credit: Thoughtful, specific responses demonstrating engagement
- Partial: Generic or superficial responses
- No credit: Missing

---

## Class 2: PyTorch Tensors

### Rubric Breakdown

| Category | Excellent (90-100%) | Proficient (75-89%) | Developing (60-74%) | Needs Improvement (<60%) | Points |
|----------|---------------------|---------------------|---------------------|--------------------------|--------|
| **Completion** (40 pts) | All exercises completed; tensor operations demonstrated; GPU tests run (or NA explained) | Most exercises complete; minor gaps; GPU tested if available | Several incomplete sections; some tensor operations missing | Many incomplete; little understanding shown | /40 |
| **Technical Understanding** (30 pts) | Demonstrates mastery of tensor concepts; correct shapes/dimensions; proper GPU usage | Good understanding; mostly correct operations; minor errors | Basic grasp; some confusion about shapes/dimensions | Fundamental misunderstanding of tensors | /30 |
| **Code Quality** (15 pts) | Clean, efficient tensor operations; appropriate use of PyTorch functions | Generally good code; mostly efficient | Code works but inefficient; poor function choices | Inefficient or incorrect tensor operations | /15 |
| **Medical Data Encoding** (10 pts) | Correctly encodes all data types (numerical, categorical, time-series, images) | Most encodings correct; minor issues | Some encodings incorrect or incomplete | Most encodings wrong or missing | /10 |
| **Documentation** (5 pts) | Excellent explanations of tensor shapes and operations | Good explanations; clear understanding | Minimal explanations | Little to no explanation | /5 |

**Total: /100 points**

---

### Detailed Scoring Criteria

#### Part 1: PyTorch Installation (5 points)
- ✓ Successfully imported PyTorch (2 pts)
- ✓ Checked CUDA availability (2 pts)
- ✓ Displayed version information (1 pt)

#### Part 2-3: Creating Tensors (15 points)
- ✓ Created scalar, vector, matrix tensors (6 pts)
- ✓ Correctly identified shapes and dimensions (4 pts)
- ✓ Created tensors using different methods (zeros, ones, randn, etc.) (5 pts)

#### Part 4: NumPy Conversion (10 points)
- ✓ NumPy to PyTorch conversion (3 pts)
- ✓ PyTorch to NumPy conversion (3 pts)
- ✓ Understood shared memory concept (4 pts)

#### Part 5: Tensor Operations (15 points)
- ✓ Element-wise operations (addition, multiplication, division) (5 pts)
- ✓ Matrix multiplication (3 pts)
- ✓ Aggregation operations (sum, mean, max, min) (4 pts)
- ✓ Operations along dimensions (3 pts)

#### Part 6: Medical Data Encoding (25 points)

**6.1 Numerical Data - Vital Signs (5 pts)**
- Full credit: Correctly created tensor from vital signs dictionary
- Partial: Tensor created but wrong dtype or shape
- No credit: Incorrect or missing

**6.2 Categorical Data - One-Hot Encoding (7 pts)**
- Full credit (7 pts): Correct one-hot encoding for blood type; understood concept; used built-in function
- Good (5 pts): Correct encoding but manual only or conceptual errors
- Partial (3 pts): Attempted but incorrect
- No credit (0 pts): Missing

**6.3 Time Series - ECG Signal (6 pts)**
- ✓ Created time-series tensor (3 pts)
- ✓ Appropriate shape for sequential data (2 pts)
- ✓ Visualization (1 pt)

**6.4 Image Data (7 pts)**
- ✓ Created 2D image tensor (grayscale) (3 pts)
- ✓ Understood (C, H, W) format for RGB (3 pts)
- ✓ Proper pixel value range (1 pt)

#### Part 7: GPU Acceleration (15 points)
- ✓ Checked device availability (3 pts)
- ✓ Moved tensors to GPU (if available) (5 pts)
- ✓ Performed GPU operations (3 pts)
- ✓ CPU/GPU speed comparison (4 pts)
- Note: Full credit if GPU not available but explanation provided

#### Part 8: Reshaping and Broadcasting (10 points)
- ✓ Correctly reshaped tensors using .view() (4 pts)
- ✓ Demonstrated broadcasting (4 pts)
- ✓ Explained broadcasting mechanism (2 pts)

#### Part 9: Exercise - Encode Patient Data (15 points)
**Expected solution:**
- ✓ Numerical features tensor (5 pts): [age, HR, BP_sys, BP_dia, temp]
- ✓ Gender one-hot encoding (5 pts): [1, 0] or [0, 1]
- ✓ Diabetes binary (2 pts): [1] or [0]
- ✓ Combined using torch.cat() (3 pts)

Excellent (15 pts): All components correct; proper concatenation; correct shape (8,)  
Good (11 pts): Minor errors in encoding or concatenation  
Fair (7 pts): Significant errors but shows understanding  
Poor (3 pts): Fundamental misunderstanding  
No credit (0 pts): Missing or completely incorrect

#### Part 10: Batch Processing (10 points)
- ✓ Created batch tensor with correct shape (4 pts)
- ✓ Normalized batch (4 pts)
- ✓ Understood batch dimensions (2 pts)

---

## Common Grading Notes

### What to Look For:

**Excellent Work Indicators:**
- Code runs without errors
- Clear understanding of concepts demonstrated
- Goes beyond requirements (e.g., additional analyses)
- Well-documented thought process
- Clean, professional code
- Insightful observations

**Red Flags:**
- Many code cells not executed
- Errors not addressed
- Copy-pasted code without understanding
- Missing reflection questions
- No comments or explanations
- Incorrect interpretations of results

### Partial Credit Guidelines:

1. **Code with minor errors:** 80-90% of full points
   - Example: Correct logic but typo in variable name

2. **Code with conceptual errors:** 60-75% of full points
   - Example: Wrong function used but shows some understanding

3. **Incomplete but correct:** 70-85% of full points
   - Example: Only completed 2 of 3 exercises but both correct

4. **Complete but incorrect:** 50-70% of full points
   - Example: All exercises attempted but fundamental misunderstanding

### Late Submission Policy:
- 10% deduction per day late
- Maximum 3 days late accepted
- After 3 days: 0 points but still must submit for course completion

---

## Feedback Guidelines

### Effective Feedback Should:

1. **Be Specific:**
   - ❌ "Good work"
   - ✅ "Excellent correlation analysis - you correctly identified glucose as the strongest predictor and explained the clinical significance"

2. **Be Constructive:**
   - ❌ "This is wrong"
   - ✅ "Your tensor shape is (768,) but should be (768, 1) for batch processing. Try using .view(-1, 1)"

3. **Encourage Learning:**
   - ❌ "You didn't do the exercise"
   - ✅ "Try the feature engineering exercise - it's a key skill for Week 3. I can help in office hours!"

4. **Highlight Strengths:**
   - Always mention what was done well
   - Encourage continued effort

### Standard Comments:

**For Excellent Work:**
- "Exceptional work! Your analysis goes beyond the requirements and shows deep understanding."
- "Great insights about [specific observation]. This kind of thinking is valuable in medical ML."
- "Excellent code quality - well-commented and efficient."

**For Good Work:**
- "Solid work overall. Consider [specific improvement] for even better results."
- "Good understanding demonstrated. Review [concept] for clarity."

**For Needs Improvement:**
- "You're on the right track, but [specific issue] needs attention. See [resource] for help."
- "Let's discuss [concept] in office hours - I can help clarify."

---

## Grading Workflow

### Recommended Process:

1. **Quick Scan (2 min/notebook):**
   - Check completion %
   - Look for major red flags
   - Note overall quality

2. **Detailed Review (10 min/notebook):**
   - Run key cells to verify
   - Check each rubric category
   - Note specific strengths/weaknesses

3. **Scoring (3 min/notebook):**
   - Assign points per category
   - Calculate total
   - Write summary feedback

4. **Return (1 min/notebook):**
   - Post grade to Blackboard
   - Add comments
   - Flag for follow-up if needed

**Total time per notebook: ~15 minutes**  
**For 20 students: ~5 hours per lab**

### Efficiency Tips:

- Use rubric strictly - don't overthink
- Create comment bank for common issues
- Grade in batches (all Part 1s, then all Part 2s, etc.)
- Use Blackboard's inline grading when possible
- Set aside "grading blocks" rather than interrupting workflow

---

## Grade Distribution Expectations

For well-designed labs with clear instructions:

**Expected Distribution:**
- A range (90-100): 40-50% of students
- B range (80-89): 30-40% of students
- C range (70-79): 10-20% of students
- D/F (<70): <10% of students

If distribution is very different:
- Too many As: Consider raising expectations
- Too many Cs/Ds: Review instructions clarity; offer more support
- Bimodal distribution: Indicates some students need intervention

---

## Special Considerations

### Google Colab Issues:
- **GPU not available:** Full credit if student documents attempt and explains
- **Runtime timeout:** Accept if student shows evidence of previous successful run
- **Installation errors:** Provide troubleshooting help; extend deadline if needed

### Accessibility:
- **Screen readers:** May need alternative formats for visualizations
- **Color blindness:** Ensure plots work in grayscale
- **Extended time:** Adjust deadline as needed per accommodations

### Academic Integrity:
- **Suspected plagiarism:** Check against other submissions and online sources
- **Identical code:** Acceptable for basic operations; suspicious for complex solutions
- **Follow institutional policy:** Document and report as required

---

## Appendix: Quick Reference

### Point Values Summary

**Class 1:**
- Setup & Libraries: 10 pts
- Data Loading: 10 pts
- Observations: 15 pts
- NumPy Operations: 10 pts
- Visualizations: 15 pts
- Correlation Analysis: 15 pts
- Simple ML: 10 pts
- Exercise: 10 pts
- Reflections: 5 pts
**Total: 100 pts**

**Class 2:**
- Installation: 5 pts
- Creating Tensors: 15 pts
- NumPy Conversion: 10 pts
- Operations: 15 pts
- Medical Encoding: 25 pts
- GPU Acceleration: 15 pts
- Reshaping/Broadcasting: 10 pts
- Patient Encoding Exercise: 15 pts
- Batch Processing: 10 pts
**Total: 100 pts**

### Grade Scale:
- A: 90-100
- B: 80-89
- C: 70-79
- D: 60-69
- F: <60

---

**Questions about grading?** Contact course coordinator or post in instructor forum.

**Last Updated:** January 2026
