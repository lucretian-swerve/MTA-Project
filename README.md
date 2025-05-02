# MTA Data Analysis: Regression, Classification, and Clustering

This repository contains the full codebase for a data analysis project using MTA Subway Customer Journey metrics. The goal of this project is to analyze subway line performance and predict or classify outcomes using a variety of machine learning methods.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Results Summary](#results-summary)
- [Contributors](#contributors)

---

## Project Overview

We analyzed data from the **MTA Subway Customer Journey Metrics** dataset to explore key performance indicators across subway lines. This project applies:

- **Regression** to model continuous outcomes such as customer journey time.
- **Classification** to categorize subway line performance into labels such as "good", "mediocre", or "bad".
- **Clustering** to uncover natural groupings among subway lines based on their performance metrics.

The dataset includes numerical features like additional train/platform time, percentage of delays, and total journey time.

---

## Project Structure

```bash
Integrators_code/
├── classification.py  # Supervised classification models
├── clustering.py      # Unsupervised clustering using k-means and hierarchical methods
├── regression.py      # Linear regression modeling
