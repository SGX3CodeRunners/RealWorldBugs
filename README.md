# RealWorldBugs

# 🧪 Project Plan: CodeRunners - Reproducibility Showdown

## Project Description

This project aims to evaluate and compare the reproducibility of **all 189 papers** from ICSE 2023 and SC24 that focus on large language models (LLMs) for code understanding tasks such as code summarization, completion, translation, and bug prediction. Our goal is to understand how reproducible these research artifacts are and to present our findings visually.

## Scope

- Reproduce results from each of the 189 selected papers.
- Score each paper on reproducibility factors including data availability, code accessibility, and ease of running experiments.
- Create a comparative scorecard for all papers.
- Build a public-facing web portal that presents reproducibility metrics, summaries, and visual comparisons.
- Submit a poster summarizing our methodology and findings to Gateways 2025.

---

## Reproduction Process

To assess reproducibility across all papers:

1. **Paper Assignment:** Each team member selects or is assigned a subset of papers to evaluate.

2. **Artifact Review:** For each paper:
   - Check for available code repositories, datasets, and documentation.
   - Note missing or incomplete components.
   - Attempt to set up the environment (preferably in a virtual environment or Docker).
   - Run key experiments or code segments.

3. **Evaluation Logging:** Log your findings including:
   - Setup and dependency issues
   - Execution success or failure
   - Comparison of outputs (if applicable)

4. **Scorecard Entry:** Fill in a standardized scorecard for each paper covering:
   - Paper accessibility
   - Code availability
   - Data availability
   - First-run success
   - Reproduction fidelity

5. **Portal Integration:** Sync results to the team’s visualization portal for tracking and comparison.

---

## Evaluation Framework

### Reproducibility Criteria

For each paper, we assess:

- **Paper Accessibility**
  - Status: [Accessible/Partially Accessible/Not Accessible]
  - Notes: How easy is it to access and interpret the work?

- **Code Availability and Usability**
  - Status: [Shared and Runnable / Shared with Issues / Not Shared]
  - Notes: Where is it hosted (e.g., GitHub)? Does it work out of the box?

- **Data Accessibility**
  - Status: [Findable and Usable / Requires Effort / Not Usable]
  - Notes: Formats, licensing, preprocessing steps

- **First Code Run Attempt**
  - Result: [Success / Partial Success / Failure]
  - Notes: Error messages, manual fixes, missing steps

---

## Contribution

We welcome contributors! Team members and external collaborators are encouraged to:

- Conduct reproduction attempts for additional papers.
- Submit new scorecard entries.
- Improve automation or analysis tools.
- Suggest features for the dashboard or portal.

Submit a pull request or open an issue to get involved.

---

# Project Overview and Task Deliverables

## 1. Project Overview

- **Project Name:** A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization
- **Objective:** Reproduce and evaluate 189 papers’ LLM-based code understanding results.
- **Goal:** Build a central dashboard to track reproducibility status and score trends. Share findings via poster and web portal.

## 2. Key Milestones and Deliverables

| Milestone | Description | Due Date | Deliverables |
|----------|-------------|----------|--------------|
| Day 1 – Kickoff | Assign papers, set up repo, define evaluation rubric | Day 1 | Team roles, README, paper list |
| Day 2 – Artifact Setup | Begin cloning/test runs on initial papers | Day 2 | Logs, notes, environment specs |
| Day 3 – Scorecard Draft | Finalize scorecard format, enter 25–50 papers | Day 3 | Preliminary dashboard, draft metrics |
| Day 4 – Portal Build | Build portal to visualize findings | Day 4 | Streamlit/Flask site, poster draft |
| Day 5 – Final Submit | Submit poster, present work, publish results | Day 5 | Final slides, PDF poster, team bio page |

---

## 3. Team Roles

- **Aaliyah:** Experiment Engineer – Sets up tasks and runs model reproductions
- **Arghavan:** Model Analyst – Compares outputs, fills scorecard gaps
- **Holy:** Portal Builder – Develops dashboard and visualization tools
- **Copernic:** Presenter – Creates poster/slide visuals and demos
- **Iyana:** Project Lead – Oversees progress, edits documentation, ensures delivery

---

## 4. Resource Requirements

- **People:** 5 team members with skills in Python, Hugging Face, Git, and Docker
- **Tools:** 
  - GitHub, Google Drive, Streamlit/Flask
  - Google Colab, Kaggle, or cloud GPUs (as needed)
  - Canva or Google Slides for poster
- **Communication:**
  - Slack, Discord, Zoom for check-ins

---

## 5. Daily Check-ins

We hold daily check-ins via [Slack or Zoom] at 10:00 AM and 7:00 PM EST to:

- Report progress
- Discuss blockers
- Assign next-day goals
- Share important discoveries

---

## 6. Risks & Mitigation

| Risk | Mitigation |
|------|------------|
| Papers missing artifacts | Contact authors, note gaps, use similar alternatives |
| Long run times | Run smaller tests, use cloud APIs, reuse partial results |
| Dependency/version conflicts | Use Docker or venv per paper |
| Coordination overload | Assign smaller batches, rotate team focus |
| Poster deadline issues | Submit early drafts, verify formatting ahead of time |

---

## 7. Conclusion

Team CodeRunners is tackling a large-scale, real-world challenge: **evaluating reproducibility across 189 cutting-edge research papers**. Our process is thorough, transparent, and open-source—contributing to the larger reproducibility conversation in software engineering and LLM research. Our portal and final poster will serve as a reference for future researchers navigating reproducibility in ML research.

