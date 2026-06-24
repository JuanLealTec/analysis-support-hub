# Analysis Support Hub

## Overview

The Analysis Support Hub is a problem-oriented educational reference resource designed to help students identify, understand, and overcome common challenges encountered while working with information, evidence, observations, findings, and conclusions.

Rather than following a sequential learning path, the Hub allows students to quickly locate a specific analysis problem and explore practical approaches, frameworks, techniques, tools, and resources that may help them move forward.

---

## Purpose

The Hub was created to support students developing Analysis & Information projects, particularly those with limited formal training in analysis methods who need practical guidance when encountering difficulties during the analysis process.

The resource focuses on helping students:

- Prepare and organize information.
- Identify patterns and relationships.
- Interpret and validate findings.
- Develop evidence-based conclusions.

---

## Intended Audience

### Primary Audience

Students enrolled in **PS5006 (Social Media and Information Technology)** who are developing Analysis & Information projects.

### Secondary Audience

Any student working on academic projects involving information organization, exploration, analysis, interpretation, validation, or conclusion development.

---

## Contents

The Hub currently includes:

- Home
- Quick Problem Finder
- About
- 13 problem-oriented reference pages

Problem pages are organized into four categories:

- Prepare Information
- Discover Patterns & Relationships
- Interpret & Validate Findings
- Develop Conclusions

Each problem page follows a consistent structure designed to support rapid problem identification and targeted exploration of possible solutions.

---

## Repository Structure

```text
analysis_support_hub/
├── README.md
├── .gitignore
├── mkdocs.yml
├── docs/
│   ├── index.md
│   ├── quick-problem-finder.md
│   ├── about.md
│   ├── problems/
│   └── assets/
└── build_notes/
    └── architecture.md
```

---

## Local Development

Install the required dependencies:

```bash
pip install mkdocs-material
pip install pymdown-extensions
```

Start the local development server:

```bash
mkdocs serve
```

The site will be available through the local address displayed in the terminal.

---

## Deployment

The site is published to GitHub Pages using **MkDocs** and the `gh-pages` branch.

Build and deploy the site with:

```bash
mkdocs gh-deploy
```

GitHub Pages should be configured as:

- Source: `Deploy from a branch`
- Branch: `gh-pages`
- Folder: `/ (root)`

---

## Author

Juan Carlos Leal González

High School Lecturer  
Tecnológico de Monterrey

---

## License

Unless otherwise noted, the educational content contained in this repository is distributed under the:

**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**

---

## Additional Documentation

Project architecture and design decisions are documented in:

```text
build_notes/architecture.md
```