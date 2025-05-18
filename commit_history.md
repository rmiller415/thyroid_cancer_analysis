# Commit History – Thyroid Cancer Risk Project

This file tracks major commits and changes made to the project. Each entry includes a summary, description, and timestamp to help document progress and rationale.

---

## Version 1.0.0  
**Date:** 2025-05-17 21:13  
**Commit Summary:**  
`Add directory check in model_iterator and save processed dataset`

**Description:**  
Used pathlib with if/elif/else logic to validate user input for directory.  
Raises error if directory does not exist or if path points to non-directory object.

Ran the dataset processing function and saved processed data as 
../GitHub/thyroid_cancer_analysis/resampled_data.pkl

---

## Model Training – Random Forests  
**Date:** 2025-05-17 23:40
**Commit Summary:**  
Saved model weights and performance metrics to disk for further analysis. 
Model data is too large to push to GitHub, but is available upon request.

**Description:**  
Trained 30 RandomForestClassifier models using various feature sets and transformations  
to evaluate model performance and identify optimal configurations. Model data is too large
to push to git, but is available upon request. 

---

##Commit History - Log Created
**Date: 2025-05-18 00:23
**Commit Summary:**
Add commit_history.md file

**Description:**
Created the commit_history.md file in `../GitHub/thyroid_cancer_analysis/`
directory. Pushed to origin. Removed erroneously named `commit_history.md.txt`.
