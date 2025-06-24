# RealWorldBugs

# Reproducing "A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization"

## Project Description

This repository is an effort to reproduce and further explore the findings presented in the paper "A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization" by MOB2022. We were intrigued by the insights into real-world bugs affecting machine learning models and aimed to replicate their analysis, and potentially extend it with our own observations. This project serves as a hands-on approach to understanding the reproducibility of research in the field of machine learning.

## Paper Abstract (from original source)

*A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization*

(Insert abstract of the paper here. I will leave this as a placeholder for you to fill in the actual abstract from the paper once you have access to it. You can find the paper associated with the dataset at the original website or through academic search engines.)

## Reproduction

To reproduce the original study's analysis, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MOB2022/MOB-dataset.git
    cd MOB-dataset
    ```

2.  **Install dependencies:**
    The original repository does not explicitly list `requirements.txt`. Based on the `.ipynb` files, you will likely need `pandas`, `numpy`, `matplotlib`, `seaborn`, and potentially `tensorflow` or `pytorch` if you delve into the model-specific aspects. It's recommended to create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install pandas numpy matplotlib seaborn jupyter
    # If you plan to work with TensorFlow or PyTorch related aspects:
    # pip install tensorflow
    # pip install torch torchvision torchaudio
    ```

3.  **Explore the data and notebooks:**
    The core of the analysis is within the Jupyter notebooks:
    *   `mob_plots.ipynb`: This notebook likely contains the code used to generate the plots and visualizations presented in the paper.
    *   `mob_study.ipynb`: This notebook probably walks through the methodology and analysis of the bugs.

    To open and run the notebooks:
    ```bash
    jupyter notebook
    ```
    This will open a browser window where you can navigate to and open the `.ipynb` files. Run the cells sequentially to reproduce the analysis.

## Findings

*   **Summary of Reproduction Success:** Were you able to successfully run all the code and reproduce the figures/results presented in the paper? What challenges did you face, if any?
*   **Key Observations:** What were the most interesting or surprising findings from your re-analysis of the data?
*   **Insights Gained:** How did this reproduction effort deepen your understanding of real-world ML bugs or reproducible science in general?
*   **Discrepancies (if any):** Did you find any differences between your results and those reported in the paper? What might be the reasons for these discrepancies?
*   **Future Work/Extensions:** What further analyses or experiments could be done based on this dataset or paper? (e.g., applying different analysis techniques, exploring specific bug types in more detail, expanding the dataset).

## Initial Evaluation of Reproducibility Artifact

### Paper Accessibility

*   **Status:** [Accessible/Partially Accessible/Not Accessible]
*   **Notes:** The paper is generally accessible through academic search engines. Understanding the nuances might require a background in machine learning and software engineering.

### Code Shared and Runnable

*   **Status:** [Shared and Runnable/Shared but Requires Effort/Not Shared/Not Runnable]
*   **Notes:** The code is shared on GitHub. It primarily consists of Jupyter notebooks and data files. Initial assessment suggests it should be runnable with proper environment setup. (You will update this after attempting to run the code).

### Data Findability and Usability

*   **Status:** [Findable and Usable/Findable but Requires Effort/Not Findable/Not Usable]
*   **Notes:** The data is directly included in the GitHub repository, making it easily findable. The data files (CSV, JSON) are in standard formats, suggesting good usability. (You will update this after attempting to use the data).

### Bonus: First Code Run Attempt

*   **Result:** [Success/Partial Success/Failure]
*   **Notes:** [Describe your experience here. Did it work on the first try? What errors did you encounter? What steps did you take to troubleshoot?]
## Contribution

Conduct your own analysis, and submit pull requests with your findings or improvements to the reproduction process


# Project Overview and Task Deliverables
## 1. Project Overview

- Project Name: A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization
- Objectives: Evaluate the reproducibility of results reported in the IEEE paper using large language models (LLMs) on multiple code understanding tasks, including code summarization, code completion, and translation.
- Scope:
  - Build a GitHub repo with experiment tracking, setup, documentation, and results.
  - Reproduce at least 2–3 major tasks and compare model performance (CodeT5, StarCoder, GPT-3.5/4).
  - Create a web portal with a reproducibility scorecard and interactive visualizations.
  - Submit a poster summarizing results to Gateways 2025.
- Timeline: 5 days (SGX3 hackathon)

## 2. Key Milestones and Deliverables

| Milestone | Description | Due Date | Deliverables |
|---|---|---|---|
| Day 1 – Project Kickoff | Team formation, IEEE paper review, role assignment, GitHub setup with README and project goals | Day 1 | Intro slide, README.md, team roles, initial repo push |
| Day 2 – Artifact Setup | Identify code/data, test reproducibility environment, begin small-scale runs | Day 2 | Artifact notes, initial tests (e.g., code summarization benchmark), logging results |
| Day 3 – Scorecard Drafting | Define reproducibility metrics, evaluate 2–3 model-task pairs, log gaps or bugs | Day 3 | Reproducibility scorecard (draft), run logs, annotated test outputs |
| Day 4 – Portal + Build | website/dashboard | Day 4 | Streamlit/Flask portal with charts, Poster to display reproducibility analysis and polish poster | poster draft (PDF/Canva/Slides) |
| Day 5 – Final Submission | Submit poster, deliver final presentation, and commit all documentation | Day 5 | Final poster + presentation deck, updated repo, portal link or local deployment |

## 3. Team Roles

- Aaliyah:Experiment Engineer – Sets up tasks and runs models for evaluation
- Arghavan:Model Analyst – Compares model outputs and scores reproducibility gaps
- Holy:Portal Builder – Develops interactive dashboard or site
- Copernic:Presenter – Creates visuals for the poster and slides
- Iyana:Lead – Tracks goals, edits README, manages daily progress

## 4. Resource Requirements

- People: 5 members with experience in Python, LLMs, Hugging Face, or Docker
- Tools:
  - Python, PyTorch, Hugging Face Transformers
  - Google Colab, Kaggle Kernels, or a cloud GPU (if needed)
  - Flask/Streamlit for portal
  - Canva or Google Slides for poster
- Communication:
  - Slack, Discord, or Teams for messaging
  - Zoom for check-ins every day at 7

## 5. Daily Check-ins

We will conduct daily check-ins at [Time, e.g., 10:00 AM and 7:00 PM EST] via [Platform, e.g., Google Meet/Slack] to discuss:

*   Progress made since the last check-in.
*   Any blockers or issues encountered (e.g., "we broke everything, help!").
*   Plans for the upcoming day.
*   Adjustments to tasks or roles as needed.


## 5. Risks & Mitigation

- Missing/incomplete benchmarks – Use archived copies, reconstruct from examples, or generate test data
- Long model runtimes – Use small samples or pretrained results, rely on hosted APIs if needed
- Tool mismatch – Use virtual environments or Docker to isolate dependencies
- Time bottlenecks – Prioritize 2 core tasks and scale from there
- Poster rejection or late submit – Submit early, check formatting guidelines, screenshot confirmation

## 6. Conclusion

Team CodeRunners will explore and evaluate the reproducibility of LLM-based code understanding models as presented in Big Code is a Big Deal. By validating benchmarks, testing models, and scoring artifacts on reproducibility, the team will produce a clear, visual, and open-source summary of results, contributing to the broader reproducibility movement in software engineering research.
