# How to add a finished project

## 1. Give the project its own repository

Name it in lowercase with dashes, for example `reactor-design-python`. Use this folder layout:

```
README.md          the write-up (template below)
requirements.txt   Python packages, one per line
data/              raw data you collected or downloaded
scripts/           your code
figures/           plots your code makes
results/           output tables
```

On the repo page, click the gear next to **About**. Add a one-line description and topics such as `chemical-engineering`, `python`, `reaction-engineering`.

## 2. Add it to your profile

Open `README.md` in your profile repository (the one named after your username) and edit it right on github.com with the pencil icon.

**Projects:** change the project's status badge to complete and add its link, or add a new row:

```markdown
| **[Project Name](https://github.com/genevievenm13/repo-name)** | One sentence on what you did and found | Python · SciPy | ![complete](https://img.shields.io/badge/complete-1f7a3a?style=flat-square) |
```

Status badges to copy:

```markdown
![complete](https://img.shields.io/badge/complete-1f7a3a?style=flat-square)
![in progress](https://img.shields.io/badge/in_progress-b26a00?style=flat-square)
![planned](https://img.shields.io/badge/planned-3b5964?style=flat-square)
```

**Featured Project:** when a new project is your strongest work, swap it in here with its best figure.

**Skills:** move tools from "Currently learning" into a main row once you've used them in a finished project. For example, move Aspen Plus after the flowsheet project.

## 3. Pin it

On your profile page, click **Customize your pins** and pin your best finished repos. You can pin up to six.

---

## Project README template

````markdown
# Project Title

**Genevieve Morales · UC Berkeley Chemical Engineering · Month Year**

One or two sentences: what problem this solves and why it matters.

![Main result](figures/main_figure.png)

## Key findings
- The single most important result, with a number.
- A second result.

## Method
What you modeled, built, or measured, and the governing equations or assumptions.

## Results
Figures and a short explanation of each.

## Limitations and next steps
- What you would do differently or next.

## Run it yourself
```bash
pip install -r requirements.txt
python scripts/main.py
```
````
