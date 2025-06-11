# COGS150 Final Project: Subject–Verb Agreement Attraction in GPT-2: A Surprisal Study

**Course**: COGS 150: Large Language Models, UCSD  
**Author**: Andrew Gibson (Andy)

## Project Overview

Humans exhibit “agreement‐attraction” illusions: a plural noun (“attractor”) can temporarily license a wrong verb form (e.g. *“The key to the cabinets are…”*). This project tests whether GPT-2 shows the same effect in its next‐token surprisal. We construct paired sentences where a singular or plural head noun is followed by either the correct verb (**is/are**) or the wrong one, with and without an attractor. We measure GPT-2’s surprisal and compare conditions.

## Repo Structure

.
├── COGS150_FinalProject_Agreement.ipynb    # primary notebook
├── README.md                               # this file
├── .gitignore                              # git ignore file
└── requirements.txt                        # pinned Python dependencies

## Getting Started

### Prerequisites

- Python 3.8+  
- [transformers](https://pypi.org/project/transformers/)  
- torch  
- pandas  
- seaborn  
- tqdm  
- scipy  

Install with:

```bash
pip install transformers torch pandas seaborn tqdm scipy
