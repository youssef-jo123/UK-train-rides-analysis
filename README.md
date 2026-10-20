# UK Train Rides Analysis

> DEPI Final Project - Idea 6 (Outstanding): data model, cleaning, analysis, forecasting and Tableau dashboard for UK train rides.

## Overview
Analyze the UK train rides dataset to answer questions of interest to decision makers, forecast next month's number of rides, daily revenue and demand per ticket class, and present everything in a Tableau dashboard.

## Team 265
| Name | Role |
|------|------|
| Youssef Khaled Abd Elatef Negm Elden | Team Leader |
| Abderhman Ahmed Ahmed Galal | |
| Eslam Safwat Yousif Ahmed | |
| Esmaeel Ayman Ebrahim Abd elhamid | |
| Omar Assad Mahmoud Hamada | |
| Shahad Rashad Ahmed Mohamed | |

## Project Phases
| Week | Focus | Deliverables | Status |
|------|-------|--------------|--------|
| 1 | Data model, cleaning, preprocessing (SQL, pandas, Matplotlib) | Cleaned dataset + preprocessing notebook | [ ] |
| 2 | Analysis questions (SQL, pandas, Matplotlib) | Set of analysis questions answerable from the data | [ ] |
| 3 | Forecasting (scikit-learn, pandas, Matplotlib) | Plots: next-month rides, daily revenue, demand per ticket class | [ ] |
| 4 | Tableau dashboard + final presentation | Dashboard, final report, presentation | [ ] |

## Repository Structure
| Folder | Content |
|--------|---------|
| docs/ | Documentation sections required by DEPI (planning, requirements, design, testing, final reports) |
| data/ | raw and processed datasets |
| sql/ | SQL scripts (data model, cleaning, analysis) |
| notebooks/ | Jupyter notebooks for each phase |
| dashboard/ | Tableau workbook and screenshots |
| reports/ | Figures and exported plots |

## DEPI Documentation Deadlines
| Item | Deadline |
|------|----------|
| Planning, Literature Review, Requirements | 16 Oct 2026 |
| System Analysis & Design | 6 Nov 2026 |
| Implementation | 30 Nov 2026 |
| Final Presentation, Testing & Reports | 4 Dec 2026 |

## Installation
```bash
git clone <repo-url>
cd uk-train-rides-analysis
python -m venv venv
pip install -r requirements.txt
```

## System Requirements
- Python 3.10+, Jupyter
- SQL database (e.g. MySQL / SQL Server / SQLite)
- Tableau (Desktop or Public)

## How to Run
1. Put the original dataset in `data/raw/`.
2. Run the notebooks in order (01 -> 03).
3. Open the workbook in `dashboard/` with Tableau.
