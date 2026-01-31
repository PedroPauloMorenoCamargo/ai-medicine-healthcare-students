# Getting Started with AI in Medicine and Healthcare

**Institution:** Insper Instituto de Ensino e Pesquisa, São Paulo, Brazil

## Welcome! 👋

This guide will help you get set up for the course and ensure you have everything you need to succeed.

## Quick Start Checklist

- [ ] **Google Account** - Required for Google Colab
- [ ] **Course Access** - Blackboard enrollment confirmed
- [ ] **Group Assignment** - Know your group members (3-4 students)
- [ ] **Communication** - Join course discussion board
- [ ] **Schedule** - Classes on Tuesdays and Thursdays - 4:30PM

## Setting Up Google Colab

### Why Google Colab?
- ✅ Free access to GPU/TPU hardware
- ✅ No installation required - runs in browser
- ✅ Pre-installed ML libraries (PyTorch, TensorFlow, NumPy, pandas)
- ✅ Easy sharing and collaboration
- ✅ Integrates with Google Drive for storage

### Getting Started with Colab

1. **Access Colab**
   - Go to [colab.research.google.com](https://colab.research.google.com)
   - Sign in with your Google account

2. **Open Your First Notebook**
   - File → Open notebook
   - Select "GitHub" tab
   - Paste course GitHub URL
   - Navigate to `week1/notebooks/Week1_Class1_Introduction_and_Colab_Setup.ipynb`

3. **Save to Your Drive**
   - File → Save a copy in Drive
   - This creates your personal copy
   - All changes auto-save to your Drive

4. **Enable GPU (when needed)**
   - Runtime → Change runtime type
   - Hardware accelerator → GPU
   - Click Save
   - ⚠️ Free tier: 12-16 hours per session, limited monthly quota

5. **Essential Colab Commands**
   ```python
   # Check GPU availability
   import torch
   print(torch.cuda.is_available())
   
   # Mount Google Drive (for loading/saving data)
   from google.colab import drive
   drive.mount('/content/drive')
   
   # Install additional packages if needed
   !pip install package-name
   ```

## Google Colab Best Practices

### 💾 Saving Your Work
- **Auto-save:** Enabled by default for Drive copies
- **Manual save:** File → Save (or Ctrl+S)
- **Checkpoints:** File → Revision history
- **Download:** File → Download → Download .ipynb

### ⚡ Managing Resources
- **Runtime limits:** 12-16 hours, then auto-disconnect
- **RAM limits:** ~12GB standard, ~25GB with Colab Pro
- **GPU limits:** Varies based on availability
- **Best practice:** Don't leave sessions idle

### 🔄 Sharing & Collaboration
- Share button → Copy link → Share with group members
- Set permissions: "Anyone with the link can view" for read-only
- Or "can edit" for collaborative work
- **Warning:** Multiple editors can overwrite each other's changes

### 📁 Organizing Your Drive
```
My Drive/
└── AI_ML_Medicine_Course/
    ├── Week1/
    │   ├── Week1_Class1_Lab.ipynb
    │   └── Week1_Class2_Lab.ipynb
    ├── Week2/
    ├── Datasets/
    │   └── diabetes.csv
    └── Projects/
```

## Alternative Setup: Local Installation

If you prefer working locally instead of Colab:

### Prerequisites
- **Python:** 3.10 or higher
- **Hardware:** 8GB+ RAM recommended, GPU optional but helpful

### Installation Steps

1. **Install Python**
   - Download from [python.org](https://www.python.org/downloads/)
   - Or use Anaconda: [anaconda.com](https://www.anaconda.com/)

2. **Create Virtual Environment**
   ```bash
   # Using venv
   python -m venv ml-medicine-env
   source ml-medicine-env/bin/activate  # On Windows: ml-medicine-env\Scripts\activate
   
   # Or using conda
   conda create -n ml-medicine python=3.10
   conda activate ml-medicine
   ```

3. **Install Required Packages**
   ```bash
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
   pip install numpy pandas matplotlib seaborn jupyter scikit-learn
   pip install pydicom fhir.resources pillow
   ```

4. **Verify Installation**
   ```python
   import torch
   import numpy as np
   import pandas as pd
   
   print(f"PyTorch version: {torch.__version__}")
   print(f"CUDA available: {torch.cuda.is_available()}")
   ```

5. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

### GPU Setup (NVIDIA Only)
- Install [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads)
- Install [cuDNN](https://developer.nvidia.com/cudnn)
- Verify with `torch.cuda.is_available()`

## Course Materials Access

### Blackboard
- **Location:** [Your institution's Blackboard URL]
- **Contents:**
  - Weekly modules with slides and readings
  - Lab notebooks and datasets
  - Assignment submissions
  - Grades and feedback
  - Discussion boards

### GitHub Repository
- **URL:** [Course GitHub repo]
- **Contents:**
  - All course materials
  - Lab notebooks (student and solution versions)
  - Additional resources
  - Code examples
- **How to use:**
  - Clone: `git clone [repo-url]`
  - Or download ZIP: Code → Download ZIP

## Python Refresher

### If You're New to Python
Complete these tutorials before Week 1:
1. [Official Python Tutorial](https://docs.python.org/3/tutorial/) (Chapters 3-5)
2. [NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html)
3. [pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)

### Key Concepts to Review
```python
# Lists and indexing
patients = [45, 52, 38, 61]
print(patients[0])  # 45

# Dictionaries
patient = {"age": 45, "bp": 120}
print(patient["age"])  # 45

# NumPy arrays
import numpy as np
vitals = np.array([120, 80, 98.6])
print(vitals.mean())  # 99.53

# pandas DataFrames
import pandas as pd
df = pd.DataFrame({
    "age": [45, 52, 38],
    "bp": [120, 135, 115]
})
print(df.describe())
```

## Getting Help

### During Class
- Raise hand for instructor help
- Collaborate with group members

### Outside Class
1. **Office Hours:** [Schedule TBD]
2. **Discussion Board:** Blackboard → Discussions
3. **Email:** mjack@insper.edu.br (allow 24-48 hours)
4. **Study Groups:** Coordinate with classmates

### Self-Help Resources
- **Python:** [Stack Overflow](https://stackoverflow.com/questions/tagged/python)
- **PyTorch:** [Official Forums](https://discuss.pytorch.org/)
- **Colab:** [FAQ](https://research.google.com/colaboratory/faq.html)
- **Course:** [GitHub Issues](link-to-repo/issues)

## Troubleshooting Common Issues

### "Module not found" error
```python
# Solution: Install missing package
!pip install package-name
# Then restart runtime: Runtime → Restart runtime
```

### "CUDA out of memory"
```python
# Solution 1: Reduce batch size
batch_size = 16  # Try 8 or 4

# Solution 2: Clear cache
import torch
torch.cuda.empty_cache()

# Solution 3: Restart runtime
```

### "Session disconnected" in Colab
- Reconnect: Runtime → Reconnect
- Rerun all cells: Runtime → Run all
- **Prevention:** Save frequently to Drive

### Slow performance
- For Colab: Enable GPU (Runtime → Change runtime type)
- For local: Check if using CUDA: `torch.cuda.is_available()`
- Reduce data/model size for testing

## Tips for Success

### 📚 Time Management
- **Before class:** Read assigned chapters
- **During class:** Take notes, ask questions
- **After class:** Complete labs within 48 hours
- **Weekly:** Review and consolidate learning

### 👥 Group Work
- Set regular meeting times
- Divide tasks but review together
- Use shared Google Drive folder
- Communicate via Slack/Discord/WhatsApp

### 💪 Best Practices
- **Save often:** Ctrl+S in Colab, commit code frequently
- **Comment code:** Future you will thank present you
- **Test incrementally:** Don't write 100 lines before testing
- **Ask early:** Don't wait until deadline to ask for help
- **Experiment:** Try variations, break things, learn

## Course Communication

### Channels
- **Announcements:** Blackboard (check daily)
- **Questions:** Discussion board (response within 24 hours)
- **Urgent:** Email instructor
- **Group:** Your preferred platform

### Response Times
- **Instructor:** Within 24-48 hours (weekdays)
- **Peers:** Vary, be patient and helpful

## Ready to Start!

✅ You have Google account
✅ You can access Colab
✅ You know your group
✅ You've reviewed Python basics
✅ You have course materials

---

**Questions?** Post on the discussion board or attend office hours. **Good luck!** 🚀
