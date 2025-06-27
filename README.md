# 🧪 CodeRunners — RealWorldBugs: A Reproducibility Showdown

Welcome to the CodeRunners' submission for HackHPC @ ADMI 2025. This project investigates the **reproducibility and openness of real-world research artifacts** from recent AI and HPC conferences by building and applying an automated scoring system.

🔗 GitHub Repository: [https://github.com/SGX3CodeRunners/RealWorldBugs](https://github.com/SGX3CodeRunners/RealWorldBugs)

---

## 🎯 Project Overview

**Project Name**: A Comprehensive Study of Real-World Bugs in Machine Learning Model Optimization  
**Objective**: Reproduce and evaluate 189 papers’ LLM-based code understanding results.  
**Goal**: Build a central dashboard to track reproducibility status and score trends. Share findings via poster and web portal.

---
## Poster Preview
<p align="center"> <img src="poster_preview.png" alt="HackHPC Poster Preview" width="700"> </p>

---

## 📅 Key Milestones and Deliverables

| Milestone           | Description                                   | Due Date | Deliverables                            |
|---------------------|-----------------------------------------------|----------|-----------------------------------------|
| Day 1 – Kickoff     | Assign papers, set up repo, define rubric     | ✅       | Team roles, README, paper list          |
| Day 2 – Artifact Setup | Clone/test initial papers                  | ✅       | Logs, notes, environment specs          |
| Day 3 – Scorecard   | Finalize format and score 25–50 papers        | ✅       | Draft dashboard, metrics                |
| Day 4 – Portal Build| Visualize results and polish                  | ✅       | Flask/Streamlit site, poster draft      |
| Day 5 – Final Submit| Finalize and present                          | ✅       | Poster, bio page, submission repo       |

---

## 🧪 Evaluation Framework

### 📌 Reproducibility Criteria

We assess each paper using the following points:

- **Paper Accessibility**  
  Status: `[Accessible / Partially Accessible / Not Accessible]`  
  Notes: Clarity of access, licensing, PDF links.

- **Code Availability & Usability**  
  Status: `[Runnable / With Issues / Not Shared]`  
  Notes: Repo links, licensing, install steps.

- **Data Accessibility**  
  Status: `[Findable / Requires Effort / Not Usable]`  
  Notes: Dataset formats, URLs, preprocessing.

- **First Code Run Attempt**  
  Result: `[Success / Partial / Failed]`  
  Notes: Errors, fixes, missing instructions.

---

## 📊 Reproducibility Scorecard (8 Criteria × 1–5 Scale)

| Category                | 1 (Poor)                         | 5 (Excellent)                         |
|------------------------|----------------------------------|----------------------------------------|
| **Code Access**        | No code provided                 | GitHub repo with license               |
| **Environment Setup**  | No install instructions          | Docker or venv setup                   |
| **Dependency Details** | No requirements mentioned        | requirements.txt, pipfile, etc.        |
| **Data Access**        | No dataset access                | Public URL, licensing clear            |
| **Result Verification**| No results                       | Logs, eval metrics shown               |
| **Reproduction**       | No run instructions              | run.sh, notebooks, containers          |
| **Citation Quality**   | No reference                     | DOI, BibTeX, or arXiv                  |
| **Testability**        | No testing tools                 | test dir, pytest, CI/CD badge          |

> 🔢 **Max Score**: 40 points → Very Low, Low, Moderate, High, Excellent

---

## ✅ Sample Papers Evaluated
A few sample papers evaluated were: 
- [HistFuzz](https://github.com/CGCL-codes/HistFuzz)
- [CCRep](https://github.com/ZJU-CTAG/CCRep)
- [CodeGenEval (Zenodo)](https://doi.org/10.5281/zenodo.7037673)
- [EXO Paravirtualization](https://github.com/nicexlab/exo)
- [Multicast-Based Allgather](https://github.com/spcl/multicast-based-allgather)

---

## Contribution

We welcome contributors! Team members and external collaborators are encouraged to:

- Conduct reproduction attempts for additional papers.
- Submit new scorecard entries.
- Improve automation or analysis tools.
- Suggest features for the dashboard or portal.

Submit a pull request or open an issue to get involved.

---
## 👥 Meet the Team

| Name        | Role                    | GitHub                                      | LinkedIn                                      | Photo Preview                         |
|-------------|-------------------------|----------------------------------------------|-----------------------------------------------|----------------------------------------|
| **Alice Doe**  | Project Lead             | [@alice-doe](https://github.com/alice-doe)      | [linkedin.com/in/alicedoe](https://linkedin.com/in/alicedoe)     | ![](team_photos/alice.jpg)  |
| **Ben Smith**  | Experiment Engineer      | [@bensmith](https://github.com/bensmith)        | [linkedin.com/in/bensmith](https://linkedin.com/in/bensmith)     | ![](team_photos/ben.jpg)    |
| **Chloe Kim**  | Model Analyst            | [@chloekim](https://github.com/chloekim)        | [linkedin.com/in/chloekim](https://linkedin.com/in/chloekim)     | ![](team_photos/chloe.jpg)  |
| **David Park** | Portal Developer         | [@davidpark](https://github.com/davidpark)      | [linkedin.com/in/davidpark](https://linkedin.com/in/davidpark)   | ![](team_photos/david.jpg)  |
| **Ella Ray**   | Poster & Docs Lead       | [@ellaray](https://github.com/ellaray)          | [linkedin.com/in/ellaray](https://linkedin.com/in/ellaray)       | ![](team_photos/ella.jpg)   |

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

We hold daily check-ins via [Slack or Zoom] at 10:00 AM, 3:00 PM, and 7:00 PM EST to:

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

