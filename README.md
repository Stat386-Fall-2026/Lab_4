# Lab 4: Exploring Patterns with pandas

## Objective

Use pandas and NumPy to conduct a deeper exploratory analysis of General
Conference talks. You will combine several DataFrame operations, create new
variables, compare observations with their groups, count phrases in talk text,
and create basic exploratory plots.

## Create your personal repository

1. Click **Use this template** and select **Create a new repository**.
2. For **Owner**, select `Stat386-Fall-2026`.
3. Name your repository using the format `your_netid_lab_4`.
4. Set the repository visibility to **Private**.
5. Click **Create repository**.

## Clone and set up the project

Clone your personal repository inside your `School/STAT_386` folder:

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

Install the project dependencies:

```bash
uv sync
```

The first time you run this command, `uv` will create a `uv.lock` file. Include
that file in your first commit.

Open the repository folder in Positron. If Positron asks you to select a Python
interpreter, select the interpreter inside the `.venv` folder created by `uv`.

## Complete the lab

Open `lab_4.qmd` and replace `Your Name` with your name. Complete every code
section and every written response. You can preview the document while you
work by running:

```bash
uv run quarto preview lab_4.qmd
```

Stop the preview by pressing `Ctrl+C` in the terminal.

Make several meaningful commits as you work. For example:

```bash
git add lab_4.qmd
git commit -m "Create keyword features"
git push
```

## Render and submit

Before submitting, restart your work from a clean session and render the final
document:

```bash
uv run quarto render lab_4.qmd
```

Commit and push both the source document and the rendered HTML file:

```bash
git add lab_4.qmd lab_4.html uv.lock
git commit -m "Complete Lab 4"
git push
```

Follow the submission directions provided in Canvas.

## Generate the follow-up reflection issue

Create a new Issue using the **Lab 4 Complete** Issue template if it is
available.

Use the following title:

```text
Lab 4 complete
```

The description can be empty. Post the Lab 4 processing command as a new
comment:

```text
@local-llm-user process config-dir: Lab_4/ in instructor-repo: Stat386-Fall-2026/Instructor_Repo
```

The command must be posted as a comment, not in the Issue description. Once
processing is complete, answer the questions in the new review Issue created
by the course collaborator.

## Before you finish

- [ ] Your name appears in the document header.
- [ ] Every code section is complete.
- [ ] Every written response is complete.
- [ ] Your term counts are case-insensitive.
- [ ] You compare raw counts with rates based on talk length.
- [ ] Every plot has a useful title and axis labels.
- [ ] `lab_4.qmd` renders without errors.
- [ ] `lab_4.html` and `uv.lock` are committed.
- [ ] All commits are pushed to GitHub.
- [ ] You answered the collaborator's questions.

## Repository contents

```text
Lab_4/
├── data/
│   ├── README.md
│   └── talks.csv
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── lab-4-complete.md
├── .gitignore
├── README.md
├── lab_4.qmd
└── pyproject.toml
```
