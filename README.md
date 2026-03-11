# Patika Dev Day 1 Kaggle Notebook

Day 1 notebook for introductory industrial computer vision workflows with OpenCV, NumPy, and Matplotlib.

## Contents

- `Day1_Kaggle_Notebook.ipynb`: main notebook
- `kernel-metadata.json`: Kaggle kernel metadata
- `requirements.txt`: local Python dependencies

## Scope

The notebook covers:

- environment checks
- image reading and writing
- BGR vs RGB visualization
- color space conversion
- blur and denoising
- histogram equalization
- ROI selection
- HSV masking
- morphology
- edge detection
- contour analysis
- 3 small synthetic mini projects

## Data Requirements

This notebook runs as-is without any external dataset. Most examples generate synthetic images directly inside the notebook.

Optional real-world datasets for extension:

- `kaustubhdikshit/neu-surface-defect-database`
  https://www.kaggle.com/datasets/kaustubhdikshit/neu-surface-defect-database
- `toqaalaaawad/metal-surfaces-defects`
  https://www.kaggle.com/datasets/toqaalaaawad/metal-surfaces-defects

The first one is already referenced inside the notebook for the steel-surface mini project.

## Local Setup

```bash
python -m venv .venv
.venv\\Scripts\\activate
pip install -r requirements.txt
jupyter lab
```

## Kaggle

The notebook is also prepared for Kaggle kernel publishing via `kernel-metadata.json`.

Default attached Kaggle dataset:

- `kaustubhdikshit/neu-surface-defect-database`

## Links

- GitHub: https://github.com/PatikaTosyali/patika-dev-day1-kaggle-notebook
- Kaggle: https://www.kaggle.com/code/oaslananka/patika-dev-day1-kaggle-notebook
