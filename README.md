<div align="center">
  <img
    src="https://avatars.githubusercontent.com/u/156722421?v=4"
    width="140"
    alt="Meihan Chen profile photo"
  />

  # Hi, I'm Meihan (Zora) Chen

  **Data Science & Applied Mathematics at UNC-Chapel Hill**

  [Personal Website](https://zoraaaa03.github.io/) 

  Scientific Computing · Applied Mathematics · Biomedical Data Science
</div>

## About Me

I work at the intersection of applied mathematics, scientific computing,
and data-driven modeling. I am particularly interested in developing
reproducible computational tools and combining mathematics with computation
to solve real-world problems in biology, from large-scale scientific
simulations to biomedical image analysis.

## Featured Work

### Open-Source Development for IBAMR

[IBAMR](https://github.com/IBAMR/IBAMR) is an open-source,
distributed-memory parallel framework for immersed-boundary and
fluid-structure interaction simulations.

I contributed `RestartCleaner` through
[merged upstream PR #1830](https://github.com/IBAMR/IBAMR/pull/1830).
The contribution adds configurable, MPI-safe checkpoint retention for
long-running simulations, including:

- C++17 filesystem-based checkpoint management
- SAMRAI configuration integration
- Dry-run and logging support
- Interface and end-to-end regression tests

My follow-up
[PR #1911](https://github.com/IBAMR/IBAMR/pull/1911)
adds persistent protection for scientifically important checkpoints.

**Technologies:** C++17, MPI-aware file management, SAMRAI, Git,
regression testing

### Retinal Vascular Network Development 

[This team project](https://github.com/YGAO0114/STOR674-Final-Project)
was completed for course STOR 674, Tools for Reproducible Data Science at UNC-Chapel Hill.
It develops a reproducible computational pipeline for studying mouse
retinal vascular development through:

- nnU-Net-based vessel segmentation
- Vascular-network reconstruction
- Morphological and topological feature extraction
- Longitudinal statistical analysis across developmental time points

My primary contribution was developing the reproducible statistical-analysis
stage. I integrated morphological and topological features across P2–P7/P7x
and implemented regression, correlation analysis, principal component
analysis, hypothesis testing, automated data validation, and reproducible
tables and visualizations.

Related merged contributions:
[PR #1](https://github.com/YGAO0114/STOR674-Final-Project/pull/1) ·
[PR #4](https://github.com/YGAO0114/STOR674-Final-Project/pull/4)

**Project stack:** Python, pandas, NumPy, SciPy, scikit-learn,
Matplotlib, pytest, PyTorch, nnU-Net, NetworkX, Jupyter

### Census Income Classification Capstone

[This capstone project](https://github.com/zoraaaa03/BTT-Capstone)
follows the full machine learning life cycle to predict whether an
individual's annual income exceeds $50,000 using the Census Income dataset.

The project includes:

- Exploratory data analysis and fairness-aware feature selection
- Missing-value imputation, feature scaling, and one-hot encoding
- Tuned logistic regression with five-fold cross-validation
- A feedforward neural network and side-by-side error analysis

The tuned logistic regression achieved 0.8055 accuracy and a 0.6775 F1 score,
while the neural network achieved 0.8572 accuracy and a 0.6839 F1 score. The
analysis also examines class imbalance, underrepresented groups, proxy
variables, and the consequences of using model predictions in financial
program eligibility workflows.

**Project stack:** Python, pandas, NumPy, scikit-learn, TensorFlow/Keras,
Matplotlib, Seaborn, Jupyter

## Research Code Availability

Additional repositories associated with manuscripts are currently private
during manuscript preparation and review. Code and reproducibility materials
will be released once publication, data-use, and collaborator permissions allow.

## Contact

- [LinkedIn](http://www.linkedin.com/in/meihanc)
- [Email](mailto:meihanchen03@gmail.com)
