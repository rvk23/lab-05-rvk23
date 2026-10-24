# Lab 05: Logistic Regression

<!-- STAT 486 · Fall 2026 -->

## Objective

Build and interpret a logistic-regression classifier for the breast-cancer dataset. You will prepare the data, evaluate predictions, interpret coefficients as log-odds and odds ratios, verify a gradient calculation, and discuss modeling assumptions.

## Before you begin

You need Git, a GitHub account, and [uv](https://docs.astral.sh/uv/getting-started/installation/) installed on your computer.

## Set up your submission repository

### 1. Create your private submission repository

On [`STAT-486-Fall-2026/lab-05`](https://github.com/STAT-486-Fall-2026/lab-05), select **Use this template** and then **Create a new repository**. Set the owner to the `STAT-486-Fall-2026-Labs` organization, name the repository exactly:

```text
lab-05-<netid>
```

For example, a student whose NetID is `jdoe42` must create `lab-05-jdoe42`. Use your institutional NetID even if it differs from your GitHub username. Make the repository **private**, then create it. Do not fork the starter repository.

### 2. Clone your repository

Copy the HTTPS URL for **your repository**, then run the following commands. Replace the NetID placeholder.

```bash
git clone https://github.com/STAT-486-Fall-2026-Labs/lab-05-<netid>.git
cd lab-05-<netid>
```

### 3. Create and lock your environment

The starter repository includes a lab-specific `pyproject.toml`. From the repository directory, run:

```bash
uv sync
```

This creates your local `.venv` and generates `uv.lock`. Keep the supplied `pyproject.toml` unchanged. Commit the generated `uv.lock` with your work, but never commit `.venv`.

### 4. Complete the lab

Open `lab-05.ipynb` in your preferred editor and configure it to use the notebook kernel in this repository's `.venv`.

Complete every code and written-response space in the notebook. Before committing, restart the kernel and run all cells in order so that your notebook contains your completed work and executes without errors.

### 5. Commit and push your work

```bash
git add lab-05.ipynb uv.lock
git commit -m "Complete Lab 05"
git push
```

## Submission

Paste the root URL of your repository into the Canvas Lab 05 submission textbox:

```text
https://github.com/STAT-486-Fall-2026-Labs/lab-05-<netid>
```

Do not open a pull request and do not upload the notebook file to Canvas.
