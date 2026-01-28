# Frequently Asked Questions (FAQ)

## General Course Questions

### Q: What background do I need for this course?
**A:** Basic Python familiarity is helpful but not required. We'll review fundamentals in Week 1-2. No prior ML experience needed - we start from scratch!

### Q: How much time should I expect to spend per week?
**A:** Approximately 5-10 hours total:
- 2 hours in class (lecture + lab)
- 2-3 hours completing labs
- 1-2 hours readings
- 1-3 hours group project work (later weeks)

### Q: Can I use my own laptop or do I need the computer lab?
**A:** Google Colab works entirely in your browser - any computer with internet access works. Local setup is optional.

### Q: What if I miss a class?
**A:** 
- Review lecture slides on Blackboard
- Complete lab notebook independently
- Coordinate with group members for group work
- Attend office hours if you need help
- Note: Attendance affects participation grade (15%)

### Q: How are groups assigned?
**A:** Groups of 3-4 students are assigned randomly in Week 1. Groups remain together for all labs and projects.

### Q: Can I change groups?
**A:** Only in exceptional circumstances. Contact instructor privately if serious issues arise.

## Technical Questions

### Q: What if Google Colab doesn't work for me?
**A:** 
1. Try different browser (Chrome recommended)
2. Check internet connection
3. Clear browser cache
4. Use incognito/private mode
5. As last resort: Set up local Python environment

### Q: How do I enable GPU in Colab?
**A:** Runtime → Change runtime type → Hardware accelerator → GPU → Save

### Q: Why does my Colab session keep disconnecting?
**A:** 
- Free tier has time limits (~12 hours)
- Idle sessions disconnect after 90 minutes
- High demand may cause earlier disconnection
- **Solution:** Save work frequently, reconnect and rerun cells

### Q: Can I use Colab Pro?
**A:** Yes, optional but not required. Pro offers:
- Longer runtimes
- More RAM
- Faster GPUs
- Priority access
- Cost: ~$10/month

### Q: What if I don't have a Google account?
**A:** You'll need to create one (free). It's required for Colab. Use your university email if preferred.

### Q: Can I use Jupyter Notebook locally instead of Colab?
**A:** Yes! See resources/Getting_Started.md for local setup instructions.

### Q: What's the difference between CPU and GPU in Colab?
**A:** 
- **CPU:** Always available, slower for large neural networks
- **GPU:** 10-50x faster for deep learning, limited availability
- For Week 1-3: CPU is sufficient
- For Week 4+: GPU highly recommended

## Dataset Questions

### Q: Where do I get the datasets?
**A:** 
- **Option 1:** Datasets load directly in Colab notebooks (easiest)
- **Option 2:** Download from course GitHub
- **Option 3:** Download from original sources (UCI, Kaggle, PhysioNet)

### Q: Can I use my own dataset for projects?
**A:** Yes, encouraged for final project! Must get instructor approval first.

### Q: Are the medical datasets real patient data?
**A:** All datasets are either:
- De-identified research datasets (HIPAA compliant)
- Public benchmark datasets
- Synthetic data for educational purposes

### Q: What if I work in healthcare - can I use data from work?
**A:** **NO, absolutely not** without proper IRB approval and data use agreements. Use provided datasets only.

## Assignment Questions

### Q: When are labs due?
**A:** 
- Labs 1-8: End of following week (7 days after assignment)
- Midterm project: Week 8
- Final project: Week 14
- See course outline for exact dates

### Q: Can I submit late?
**A:** 
- Up to 24 hours late: 10% penalty
- 24-48 hours late: 25% penalty
- More than 48 hours: Case-by-case (contact instructor)
- Extensions available for documented emergencies

### Q: How are group assignments graded?
**A:** 
- Base grade: Group submission score
- Individual grade: Base ± up to 10% based on peer evaluations
- All group members complete confidential peer evaluation
- Consistently low ratings may result in further deduction

### Q: What happens if a group member doesn't contribute?
**A:** 
- Document issues in peer evaluations
- Contact instructor if severe
- Peer evaluation affects individual grade
- Extreme cases: Individual may be removed from group

### Q: Can I redo assignments for better grade?
**A:** No resubmissions, but can ask questions before deadline for feedback.

### Q: Are there extra credit opportunities?
**A:** Occasionally announced in class. Not guaranteed.

## Content Questions

### Q: Do I need to know calculus?
**A:** Helpful but not required. We focus on intuition over mathematical proofs. Basic derivative concepts will be explained when needed.

### Q: Do I need to know linear algebra?
**A:** Basic concepts (vectors, matrices) helpful but reviewed in class. Week 1 covers what you need.

### Q: Do I need statistics background?
**A:** Introductory statistics helpful. We cover essential statistical concepts when needed.

### Q: What programming language is used?
**A:** Python 3, specifically:
- PyTorch for deep learning
- NumPy for numerical computing
- pandas for data manipulation
- matplotlib/seaborn for visualization

### Q: Can I use TensorFlow instead of PyTorch?
**A:** Course uses PyTorch, but you may explore TensorFlow independently. Submit assignments in PyTorch.

### Q: Will we learn about [specific ML technique]?
**A:** Check the course outline. Coverage includes:
- ✅ Supervised learning (regression, classification)
- ✅ Neural networks (fully connected, CNN, RNN)
- ✅ Model evaluation and validation
- ✅ Transfer learning
- ⚠️ Limited: Unsupervised learning, reinforcement learning
- ❌ Not covered: GANs, advanced optimization, research-level topics

## Project Questions

### Q: When do we choose final project topics?
**A:** Week 10. Start thinking about interests early!

### Q: Can projects be on non-medical topics?
**A:** No, must be healthcare/medical AI related.

### Q: Can I continue my project after the course?
**A:** Yes, encouraged! Some become papers/theses.

### Q: Do we need real patients for projects?
**A:** **NO.** Use public datasets only.

### Q: Can I do project individually instead of group?
**A:** No, all projects are group-based to simulate real-world collaboration.

### Q: What makes a good final project?
**A:** 
- Clear clinical question
- Appropriate dataset
- Rigorous evaluation
- Well-documented code
- Clinical interpretation
- See rubric for details

## Grading Questions

### Q: What's the grading scale?
**A:** Standard scale:
- A: 90-100%
- B: 80-89%
- C: 70-79%
- D: 60-69%
- F: < 60%

### Q: Can I see my grades?
**A:** Yes, all grades posted on Blackboard within 1 week of submission.

### Q: Can I dispute a grade?
**A:** Yes, within 1 week of grade posting. Email instructor with specific concerns and justification.

### Q: What if my group gets different grades?
**A:** Possible if peer evaluations show unequal contribution. Base grade is same, but individual adjustments up to ±10%.

## Getting Help

### Q: Where do I ask questions?
**A:** 
1. **Quick questions:** During class
2. **Technical help:** Discussion board (TAs monitor)
3. **Private concerns:** Email instructor
4. **Complex questions:** Office hours

### Q: When are office hours?
**A:** [Schedule TBD]. Posted on Blackboard and announced in Week 1.

### Q: Can I email the instructor directly?
**A:** Yes, but prefer discussion board for technical questions so everyone benefits. Use email for private matters.

### Q: How quickly will I get help?
**A:** 
- Discussion board: Within 24 hours (weekdays)
- Email: Within 24-48 hours (weekdays)
- Office hours: Immediate
- Don't wait until deadline to ask!

## Career & Beyond

### Q: Will this course prepare me for medical AI research?
**A:** Yes! This is an excellent foundation. For research, consider:
- Advanced courses in ML/statistics
- Reading current papers
- Joining research lab
- Attending conferences (MIDL, MICCAI, ML4H)

### Q: Can this course help me get a job in medical AI?
**A:** Absolutely! This course provides:
- Fundamental skills
- Practical projects for portfolio
- Understanding of healthcare data
- Relevant experience for roles in:
  - Medical imaging companies
  - Healthcare AI startups
  - Pharma/biotech AI teams
  - Clinical informatics

### Q: Should I pursue ML or focus on medicine?
**A:** Both! Medical domain expertise + ML skills is a powerful, rare combination. This course helps you evaluate your interests.

### Q: Can I publish work from this course?
**A:** Exceptional final projects may lead to publications. Discuss with instructor.

### Q: Will we learn about FDA approval for medical AI?
**A:** Yes, covered in Week 9 (Clinical Validation & Deployment).

---

**Still have questions?** 
- Post on Discussion Board
- Attend Office Hours  
- Email Instructor

**Question not listed?** Let us know and we'll add it! 📧
